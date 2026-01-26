---
order: 1.9
title: LuckFox Pico Ultra W
---

:::info:true LuckFox Pico Ultra W

![](./luckfox-pico-ultra-w-2.jpg){width=995px height=654px}

:::

Для прошивки LuckFox Pico Ultra W необходимо:

-  Скачать прошивку по [ссылке](https://ftp.air-link.space/downloads/astra/firmware/astra_eye_ultra_w-latest.zip)

-  Скачать [SocToolKit](https://ftp.air-link.space/downloads/astra/SocToolKit_v1.98_20240705_01_win.zip) и установить [драйвер](https://ftp.air-link.space/downloads/astra/DriverAssitant_v5.12.zip) для Windows

-  Подключить плату к компьютеру с помощью **USB Type-C кабеля** из комплекта

-  Перевести устройство в режим прошивки: Зажать кнопку **Reset**. Не отпуская Reset, зажать кнопку **Boot**. Отпустить **Reset**, затем отпустить **Boot.**

-  Открыть **SocToolKit.exe**

-  В открывшемся окне из выпадающего списка выбрать чип **RV1106**

[image:./luckfox-pico-ultra-w-3.png::Выбор чипа RV1106:0,0,100,100:75::758px:399px:center]

-  В левом верхнем углу выбрать интерфейс **USB**. В выпадающем списке появится устройство с меткой **"Maskrom..."** -- выберите его

-  Нажать кнопку **Firmware...** и выбрать файл прошивки update.img

[image:./luckfox-pico-ultra-w-2.png::Выбор интерфейса и метки:0,0,100,100:74::910px:642px:center]



-  Нажать **Upgrade** и дождаться завершения установки

[image:./luckfox-pico-ultra-w-4.png:: Успешное завершение установки:0,0,100,100:74::1185px:587px:center]

-  После завершения прошивки **отключить питание по USB**

   :::note:true ВАЖНО

   Для прошивки понадобится:

   -  Кабель из комплекта

   -  SD накопитель от **30 Мбит (v30)**

   :::