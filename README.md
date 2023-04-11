# QA_Guru_HomeWork_15_17
Домашнее задание 17

Задание

Сделать пример конфигурации для WEB тестов:
1. Имя браузера
2. Версия браузера
3. Локальный или удаленный (RemoteWebDriver)

Сделать два вида конфигурационных файлов:
1. Для локального запуска на chrome
2. Для удаленного запуска на selenoid
Сделать возможность с помощью одной системной переменной переключать запуск с локального на удаленный.


Exercise

Make an example configuration for WEB tests:
1. Browser name
2. Browser version
3. Local or remote (RemoteWebDriver)

Make two kinds of configuration files:
1. To run locally on chrome
2. For remote launch on selenoid
Make it possible to switch startup from local to remote using one system variable.


To run web tests locally:
```shell
gradle clean test -DtestType=local
```


To run web tests remotely:
```shell
gradle clean test -DtestType=remote
```
