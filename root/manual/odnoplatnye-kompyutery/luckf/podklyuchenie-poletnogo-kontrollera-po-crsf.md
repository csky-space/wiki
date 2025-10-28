---
order: 3
title: Схема подключение полетного контроллера по CRSF
---

Подключаем TX, RX и GND к полетному контроллеру, как показано на схеме.\
В настройках Astra указываем скорость CRSF: 420000; CRSF: полетный контроллер. После настройки полетного контроллера и Luckfox Pico Ultra W\
\
Для Ardupilot:

-  устанавливаем скорость полетного контроллера: 57600;

-  выбираем протокол RCIN (23) ( Configex->Full Parameter list-> Serial ).

![](./podklyuchenie-poletnogo-kontrollera-po-crsf.png "Подключение полетного контроллера по CRSF."){width=1824px height=978px}