---
order: 1.8
title: Подключение полетного контроллера по CRSF
---

Подключаем TX, RX и GND к полетному контроллеру, как показано на схеме.\
\
В выпавшем окне Astra указываем скорость CRSF: **420000**; CRSF режим: **полетный контроллер**. После настройки полетного контроллера и Luckfox Pico Ultra W

[highlight:lemon-yellow]Для Ardupilot[/highlight]:

-  устанавливаем скорость полетного контроллера: **57600**

-  выбираем протокол **RCIN (23)** ( Config->Full Parameter list-> Serial )

[highlight:peach]Для BetaFlight[/highlight]:

-  Вкладка **Ports**->Активировать **Serial RX** для выбранного порта

-  Вкладка **Receiver**-> Receiver Mode: **Serial**->Seriak Receiver Provider: **CRSF**

   Сохранить и перезапустить

   :::info:true LuckFox Pico Ultra W

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-8.png){width=1464px height=745px}

   :::

   :::info:true LuckFox  Pico Pro max

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-7.png){width=1567px height=1008px}

   :::

   :::info:true Raspberry Pi 4

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-9.png){width=1568px height=1354px}

   :::

   :::info:true Raspberry Pi 5

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-10.png){width=1568px height=1354px}

   :::


