# DHCP Server

Роли для управления **DHCP** Сервером

## Mikrotik

### add dhcp_server mikrotik

Создание **DHCP** Сервера на интерфейсе

- Обязательные параметры

    `dhcp_server` - название DHCP Сервера (например `DHCP_SERVER1`)

    `interface` - название интерфейса на который привязать сервер (например `ether1 `)

    `address_pool` - название пула IP-адресов (например `dhcp_pool1`)

### remove dhcp_server mikrotik

Удаление **DHCP** Сервера 

- Обязательные параметры
    
    `dhcp_server` - название DHCP-сервера

### enable dhcp_server mikrotik

Активация **DHCP** Сервера 

- Обязательные параметры
    
    `dhcp_server` - название DHCP-сервера

### disable dhcp_server mikrotik

Деактивация **DHCP** Сервера

- Обязательные параметры
    
    `dhcp_server` - название DHCP-сервера


### set dhcp_server mikrotik

Редактирование параметров **DHCP** Сервера
 
- Обязательные параметры
    
    `dhcp_server` - название DHCP-сервера

    `interface` - название интерфейса на который привязать сервер (например `ether1 `)

    `address_pool` - название пула IP-адресов (например `dhcp_pool1`)

    `rename_dhcp_server` - новое название DHCP Сервера

## Cisco

### config ipaddress interface cisco

- Обязательные параметры

    `local_hostname` - local hostname
