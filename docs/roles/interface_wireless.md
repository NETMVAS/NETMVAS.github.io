# Interface: Wireless

Роли для настройки Wireless интерфейсов

## Mikrotik

### enable wireless interface mikrotik

Активировать заданный **Wireless** интерфейс 

- Обязательные параметры

    `wireless_interface` - название Wireless интерфейса

### disable wireless interface mikrotik

Деактивировать заданный **Wireless** интерфейс 

- Обязательные параметры

    `wireless_interface` - название Wireless интерфейса

### set wireless interface mikrotik

Изменить конфигурацию заданного **Wireless** интерфейса 

- Обязательные параметры

    `wireless_interface` - название Wireless интерфейса

    `ssid` - SSID сети

    `mode` - #TODO

    `security_profile` - #TODO

    `hide_ssid` - Скрыть SSID? yes/no в кавычках (например `"yes"`)

### add wireless security profile mikrotik

Добавить профиль безопасности **Wireless** интерфейса

- Обязательные параметры

    `security_profile` - название профиля

    `mode` - 

    `password` - Пароль

- Опциональные параметры

    `auth_types` - тип авторизации (по умолчанию `wpa2-psk`)

### remove wireless security profile mikrotik

Удалить указанную конфигурацию профиля безопасности **Wireless** интерфейса

- Обязательные параметры

    `security_profile` - название профиля безопасности

### set wireless security profile mikrotik

Изменить конфигурацию профиля безопасности **Wireless** интерфейса

- Обязательные параметры

    `security_profile` - название профиля безопасности

    `rename_security_profile` - новое название профиля безопасности

    `mode` - #TODO

    `password` - Пароль

- Опциональные параметры

    `auth_types` - тип авторизации (по умолчанию `wpa2-psk`)

## Cisco

### role

- Обязательные параметры

- Опциональные параметры