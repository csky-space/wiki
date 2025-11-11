---
order: 1.8
title: Подключение полетного контроллера по CRSF
---

Подключаем TX, RX и GND к полетному контроллеру, как показано на схеме.\
\
В выпавшем окне Astra указываем скорость CRSF: **420000**; CRSF режим: **полетный контроллер**. После настройки полетного контроллера и Luckfox Pico Ultra W\
[highlight:peach]Для BetaFlight[/highlight]:

-  Вкладка **Ports**->Активировать **Serial RX** для выбранного порта

-  Вкладка **Receiver**-> Receiver Mode: **Serial**->Seriak Receiver Provider: **CRSF**

   Сохранить и перезапустить

[highlight:lemon-yellow]Для Ardupilot[/highlight]:

-  устанавливаем скорость полетного контроллера: **57600**

-  выбираем протокол **RCIN (23)** ( Config->Full Parameter list-> Serial )

   :::info:true LuckFox Pico Ultra W

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-4.png){width=1824px height=1055px}

   :::

   :::info:true LuckFox Pico Pro max

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-2.png){width=1369px height=1167px}

   :::

   :::info:true Raspberry Pi 4

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-5.png){width=1568px height=1354px}

   :::