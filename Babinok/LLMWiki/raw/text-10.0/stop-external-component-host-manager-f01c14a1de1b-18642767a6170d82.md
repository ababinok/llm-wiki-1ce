# Остановка «Менеджера хостов внешних компонент»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/stop-external-component-host-manager/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/stop-external-component-host-manager/index.html
> SHA256: d52a962374ec5a35620b2580a057d1d26f4dc1c678489bfcca709013e341d665
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Чтобы остановить «Менеджер хостов внешних компонент», выполните следующие действия:

- Windows
- Linux

1. В строке поиска Windows введите «Службы».
2. Запустите приложение
  
  Службы
  
  (
  
  Services
  
  ).
3. Найдите в списке службу
  
  `1c-enterprise-echostmanager`
  
  .
4. Нажмите
  
  Остановить
  
  в контекстном меню.

В случае успешной остановки служба станет неактивной.

В списке служб Windows служба 1c-enterprise-eschostmanager после остановки не имеет состояния «Выполняется»; это признак успешной остановки в примере. [Описание иллюстрации](../figures/4bc726135b0e53eeab45bcf9744e64870f7918ec8b698b057ba6aa5ede4ba502-4fb6f4466745d65a.md)

## Быстрая остановка

«Менеджер хостов внешних компонент» поддерживает режим **быстрой остановки**. В этом режиме менеджер старается закончить работу максимально быстро, не дожидаясь завершения всех операций. Мы рекомендуем использовать этот режим только опытным администраторам.

Выполните описанные ниже действия для быстрой остановки «Менеджера хостов внешних компонент».

- Windows
- Linux

1. В строке поиска Windows введите «cmd» или «Командная строка».
2. Нажмите по найденному приложению правой кнопкой мыши и выберите **Запуск от имени администратора** в контекстном меню.
3. В командной строке выполните следующую команду (указанная ниже версия менеджера может отличаться от установленной у вас версии):
  
  ```powershell
  "C:\Program Files\1C\1CE\components\1c-enterprise-echostmanager-9.1.9+17-x86_64\bin\1ce-echostmanager.exe" stop --fast --pidfile C:\ProgramData\1C\1CE\instances\1c-enterprise-echostmanager\daemon.pid
  ```

Чтобы получить справку по команде `stop`, выполните:

```powershell
"C:\Program Files\1C\1CE\components\1c-enterprise-echostmanager-9.1.9+17-linux-x86_64\bin\1ce-echostmanager.exe" help stop
```
