---
order: 0.8
title: Подключение полетного контроллера по Mavlink к Ardupilot или Inav (6 и выше)
---

Подключаем TX, RX и GND к полетному контроллеру, как показано на схеме. В Mission Planner устанавливаем скорость полетного контроллера: **115200 (115)** и протокол **MAVLink2 (2)** (Config->Full Parameter list-> SerialX).\
В настройках Astra и указываем скорость Mavlink : **115200**.

Для настройки **Ardupilot** может потребоваться изменить следующие параметры:\
**SYSID_MYGCS : 255**\
**RC_OVERRIDE_TIME** : 1-3 секунды (время через которое после потери сигнала автопилот переключится на обычную связь или сработает failsafe)\
**RC_OPTIONS** : снимите флаг ignore MAVLink Overrides если он используется

:::info:true LuckFox Pico Ultra W

![](./podklyuchenie-poletnogo-kontrollera-po-mavlink-k-4.png){width=1757px height=929px}

:::

:::info:true LuckFox Pico Pro max

![](./podklyuchenie-poletnogo-kontrollera-po-mavlink-k-3.png){width=1370px height=1179px}

:::

:::info:true Raspberry Pi 4

![](./podklyuchenie-poletnogo-kontrollera-po-mavlink-k.png){width=1396px height=1204px}

:::

:::note 

ВАЖНО: Необходимо полетный контроллер и LuckFox Pico Ultra W должны быть настроены на одну скорость. Полетный контроллер подключаем через USB к компьютеру и в Mission Planner настроить скорость и протокол (onfigex->Full Parameter list-> Serial)

ВАЖНО: Настройка полетного контроллера осуществляется без подачи внешнего питания.

:::