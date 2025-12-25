---
order: 7
title: Обновления
---

:::lab:true Astra 1.7.2

## Astra 1.7.2

### Основные изменения

-  Добавлен инструмент прошивки EEPROM адаптеров с чипом Macrosilicon MS2107(должен работать и с MS2106, но осторожно, не тестировалось!)

### Исправлено

-  Интерфейс настройки Astra

-  Установка параметров ardupilot через Mission Planner или QGC(MAVLINK_MSG_ID_PARAM_SET)

**Ссылки на прошивки:**

[LuckFox Pico Ultra W](https://ftp.air-link.space/downloads/astra/firmware/astra_eye_ultra_w-1.7.2-prerelease.zip)

[Raspberry Pi 4 и 5](https://ftp.air-link.space/downloads/astra/firmware/astra-raspios-1.7.2-prerelease.zip)

[LuckFox Pico Pro Max](https://ftp.air-link.space/downloads/astra/firmware/sd_card_astra_eye_max-1.7.2-prerelease.zip)

:::

:::lab:true Astra 1.7.1 (только для платы Ultra W)

## Astra 1.7.1

### Исправлено

-  Интерфейс настройки Astra

**Ссылка на прошивку:**

[LuckFox Pico Ultra W](https://ftp.air-link.space/downloads/astra/firmware/astra_eye_ultra_w-1.7.1-prerelease.zip)

:::

:::lab:true Astra 1.7.0

## Astra 1.7.0

### Основные изменения

-  Адаптивный битрейт (АБР). Битрейт подстраивается в указанном диапазоне в зависимости от пропускной способности сети. Доступно при управлении через браузер и на платах LuckFox. Работает с CSI и USB камерами. АБР поможет не потерять картинку и управление в плохих условиях связи.

-  Возможность выгрузки логов для отладки(пока не используем)

-  Сообщение при отсутствии подключения

-  Подсказки по пунктам настроек в интерфейсе

### Критические изменения

-  Доработана привязка устройств

-  Улучшена безопасность данных

### Улучшено

-  Производительность USB камер. Теперь можно использовать адаптеры с большим разрешением по сырому кадру(YUYV). Но будьте внимательны, на luckfox серьезные проблемы с питанием, для мощных адаптеров лучше использовать внешнее питание.

### Исправлено

-  Исправление проверки доступности сервера

-  Исправление сообщений Mavlink телеметрии

-  Исправление завершения работы камеры CSI

**Ссылки на прошивки:**

[LuckFox Pico Ultra W](https://ftp.air-link.space/downloads/astra/firmware/astra_eye_ultra_w-1.7.0-prerelease.zip)

[Raspberry Pi 4 и 5](https://ftp.air-link.space/downloads/astra/firmware/astra-raspios-1.7.0-prerelease.zip)

[LuckFox Pico Pro Max](https://ftp.air-link.space/downloads/astra/firmware/sd_card_astra_eye_max-1.7.0-prerelease.zip)

:::
