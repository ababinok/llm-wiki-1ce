# Технологический журнал «1С:Предприятия»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/1c-enterprise-tech-log/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/1c-enterprise-tech-log/index.html
> SHA256: 9abffb513fc9f778acbafeaab4cb8768714a65b240a5ef6135ab8cf984c37572
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Если в обмене сообщениями участвуют информационные базы «1С:Предприятия», вы можете контролировать обмен с их стороны с помощью [технологического журнала](https://its.1c.ru/db/v83doc#bookmark:adm:TI000000446).

В технологическом журнале для контроля сервисов интеграции используются события **EXCP** и **SINTEG**. Исключения **EXCP** могут возникать при обработке очередей, при попытке получить или отправить сообщения в «1С:Предприятие.Элемент». События **SINTEG** используются для протоколирования работы механизмов сервисов интеграции.

## Настройка журнала

Для настройки параметров технологического журнала и механизма генерации дампов памяти используется файл [logcfg.xml](https://its.1c.ru/db/v8327doc#bookmark:adm:TI000000393). Этот файл следует поместить в каталог конфигурационных файлов системы «1С:Предприятие». Например, если сервер «1С:Предприятия» установлен на компьютере, работающем под управлением ОС Windows, то файл настройки технологического журнала необходимо поместить в каталог `C:\Program Files\1cv8\conf`.

Ниже приведен пример настройки журнала для записи событий **EXCP** и **SINTEG**. Файлы журнала сохраняются в подкаталоги `EXCP` и `SINTEG` каталога `C:\Logs\SERVER`, а дампы — в каталог `C:\Dumps`. Срок хранения файлов — 24 часа.

```xml
<?xml version="1.0"?>
<config xmlns="http://v8.1c.ru/v8/tech-log">
   <dump location="C:\Dumps\" create="1" type="3" externaldump="1"/>
   <log location="C:\Logs\SERVER\EXCP" history="24">
      <event>
         <eq property="name" value="EXCP"/>
      </event>
      <property name="all"/>
   </log>
   <log location="C:\Logs\SERVER\SINTEG" history="24">
      <event>
         <eq property="name" value="SINTEG"/>
      </event>
      <property name="all"/>
   </log>
</config>
```

## Примеры сообщений

При отправке сообщения в «1С:Предприятие.Элемент» в технологический журнал записывается событие **SINTEG**, у которого в свойстве **Func** указано **sendMessage**:

```text
00:05.377000-15995,SINTEG,0,process=rphost,p:processName=ESB_shop,OSThread=1896,SrvcName=СервисМагазина,ChannelName=СетьМагазинов_ИзМагазина,ExtSrvcURL=http://localhost:9090/applications/StoreNetwork,ExtSrvcUsr=shop,Func=sendMessage,MessageId=bbaa94a4-b37a-49cf-bc09-d4223e7506ff,BodySize=759
```

Если сообщение не удается отправить, то в технологический журнал записывается исключение **EXCP**.

При получении сообщения из «1С:Предприятие.Элемента» и записи его в очередь обработки сообщений информационной базы в технологическом журнале появляется событие **SINTEG**, у которого в свойстве **Func** указано **receiveMessage**:

```text
00:05.439033-32,SINTEG,0,process=rphost,p:processName=ESB_office,OSThread=17720,SrvcName=СервисОфиса,ChannelName=СетьМагазинов_ВОфис,ExtSrvcURL=http://localhost:9090/applications/StoreNetwork,ExtSrvcUsr=office,Func=receiveMessage,MessageId=bbaa94a4-b37a-49cf-bc09-d4223e7506ff,BodySize=759
```

Если при обработке полученного сообщения возникнет исключение, то в технологический журнал будет записано событие **EXCP**, содержащее описание ошибки и место ее возникновения.

## См. также

- [Методика анализа проблем интеграции «1С:Шины» с информационными базами на платформе «1С:Предприятие»](https://its.1c.ru/db/metod8dev/content/5997/hdoc)
