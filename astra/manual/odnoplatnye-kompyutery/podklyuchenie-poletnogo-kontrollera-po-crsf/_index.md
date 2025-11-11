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

   [image:./podklyuchenie-poletnogo-kontrollera-po-crsf-6.png:::6.59892685340468,17.897457846771687,93.3793347885895,65.83260718462873:::1568px:1133px:center]

   :::

   :::info:true LuckFox Pico Pro max

   [image:./podklyuchenie-poletnogo-kontrollera-po-crsf-7.png:::0,13.266647075229363,99.94168441753956,74.46844348831576:::1568px:1354px:center]

   :::

   :::info:true Raspberry Pi 4

   ![](./podklyuchenie-poletnogo-kontrollera-po-crsf-5.png){width=1568px height=1354px}

   :::