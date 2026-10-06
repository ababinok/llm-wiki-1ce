# Настройка «Менеджера хостов внешних компонент»

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/configure-external-component-host-manager/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/configure-external-component-host-manager/index.html
> SHA256: c0f298b307d54d72db4e0c94780aae2036079fdacb68b4c78ecbee77c7559496
> SnapshotCreated: 2026-10-05
> Rendition: verified text

Сетевые настройки «Менеджера хостов внешних компонент» хранятся в файле **echostmanager.yml**. Он располагается:

- Windows
- Linux

```text
C:\ProgramData\1C\1CE\instances\1c-enterprise-echostmanager\config\echostmanager.yml
```

## Атрибуты файла

- **network-interfaces**
  
  Содержит описание точек подключения (**endpoints**) к gRPC-сервисам для взаимодействия с «Менеджером хостов внешних компонент». Адрес по умолчанию `127.0.0.1:4000`.
  
  - **threads**
    
    Настройка потоков, выделяемых для обслуживания конечной точки (необязательная секция).
    
    - **acceptor-thread-count**
      
      Число потоков, осуществляющих подключение новых клиентов (значение по умолчанию равно `1`).
    - **selector-thread-count**
      
      Число потоков, осуществляющих прием сетевых запросов (значение по умолчанию равно `10`).
    - **worker-thread-count**
      
      Число потоков, осуществляющих обработку запросов для установленных соединений (значение по умолчанию равно количеству ядер, которое определяет `java.lang.Runtime#availableProcessors`). Для реальной эксплуатации рекомендуется устанавливать значение больше. При этом слишком больших значений (> 500) рекомендуется избегать, так как сильно возрастают накладные расходы на переключение потоков и блокировки.
- **hosts**
  
  Содержит описание настроек запускаемых хостов внешних компонент.
  
  - **address**
    
    IP-адрес, по которому будет осуществляться взаимодействие с процессами хостов внешних компонент. По умолчанию `127.0.0.1`.
  - **port-range**
    
    Задает диапазон портов, на которых может быть запущен процесс хоста внешних компонент.
    
    - **start**
      
      Начальный порт диапазона. По умолчанию `4001`.
    - **end**
      
      Конечный порт диапазона. По умолчанию `4499`.

## Пример файла echostmanager.yaml

```yaml
echostmanager:
  network-interfaces:
    private:
      endpoints:
        - 127.0.0.1:4000
      threads:
        selector-thread-count: 1
        worker-thread-count: 1
        acceptor-thread-count: 1
  hosts:
    address: 127.0.0.1
    port-range:
      start: 4001
      end: 4499
```
