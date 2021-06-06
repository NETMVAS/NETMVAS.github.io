# DHCP Client

Роль для настройки DCHP Клиента

## Mikrotik

### add dhcp_client mikrotik

Добавить **DHCP** Клиент

- Обязательные параметры

    `interface` - название интерфейса (напр. `ether1`)

    `default_route` - Указывает, добавлять ли маршрут по умолчанию. yes или no, обязательно в кавычках. (например `"yes"`)

### remove dhcp_client mikrotik

Удалить **DHCP** Клиент
 
- Обязательные параметры

    `numbers_dhcp_client` - Указывает на номер интерфейса. (например `0`)

### enable dhcp_client mikrotik

Активировать **DHCP** Клиент
 
- Обязательные параметры

    `numbers_dhcp_client` - Указывает на номер интерфейса. (например `0`)

### disable dhcp_client mikrotik

Деактивировать **DHCP** Клиент
 
- Обязательные параметры

    `numbers_dhcp_client` - Указывает на номер интерфейса. (например `0`)

### set dhcp_client mikrotik

Редактировать данные **DHCP** Клиента
 
- Обязательные параметры

    `numbers_dhcp_client` - Указывает на номер интерфейса. (например `0`)

    `interface` - название интерфейса (напр. `ether1`)

    `default_route` - Указывает, добавлять ли маршрут по умолчанию. yes или no, обязательно в кавычках. (например `"yes"`)

## Cisco

### add dhcp_client cisco

Добавить **DHCP** Клиент

- Обязательные параметры

    `interface` - номер интерфейса

### remove dhcp_client cisco

Удалить **DHCP** Клиент

- Обязательные параметры

    `interface` - номер интерфейса
