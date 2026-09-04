---
order: 2
title: Руководство по быстрому запуску
---

Настройки видео вынесены во вкладку General, рядом с настройками видео QGroundControl.

Доступны следующие три настройки:

-  Enabled - включает или отключает видео;

-  Autotune gstreamer to receive video - автоматически настраивает источник и порт в QGroundControl в разделе Fly View. Полезно, если вы не хотите указывать их вручную;

-  UDP port -порт UDP, на который будет отправляться видео

#### **1\. Краткая инструкция**

-  Должен быть включен comm link.

-  Видео включено в Application Settings->General->Airlink Stream Bridge- >Enabled.

-  Порты в Application Settings->General->Airlink Stream Bridge->UDP port и в Application Settings->General->Fly View->Video Settings-> UDP Port совпадают.

-  Application Settings->General->Fly View->Video Settings->Source установлен в UDP h.265 Video Stream.

#### **2\. Получение видео с Air-link**

   Air-link соединяется с Airlink Stream Bridge (далее – ASB), поставляющимся вместе с нашим установщиком QGroundControl, и отправляет ему видео. После получения видео ASB начинает его ретрансляцию на указанный UDP-порт . 

   Порт QGroundControl (в разделе General->Fly View->Video Settings- >UDP Port) должен совпадать с портом ASB, а также источник должен быть установлен в UDP h.265.

#### 3\.Настройки по умолчанию

-  Enabled – выключено; 

-  Autotune gstreamer to receive video – включено; 

-   UDP port - 9050

#### 5\. Создание линка для Air-link

   Перейдите на вкладку Application Settings->Comm Links. В нижней части окна нажмите “Add” - появится следующее окно.

   Введите email и пароль от вашего Air-link аккаунта. Если аккаунт ещё не создан - вы можете зарегистрироваться. Нажмите «Refresh» и в списке рядом выберите номер вашего модема. Нажмите «OK» – линк будет создан.