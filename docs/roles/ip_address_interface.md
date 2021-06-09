# IP Address: Interface

## Mikrotik

### add ip_address interface mikrotik

Создать интерфейс **ip address**

- Обязательные параметры

  `interface` - интерфейс (например `wlan1`)

  `address` - IP-адрес (например `192.168.88.1\24`)

### remove ip_address interface mikrotik

Удалить интерфейс **ip address**

- Обязательные параметры

  `numbers_ip_address` - номер интерфейса который нужно удалить

### enable ip_address interface mikrotik

Активировать интерфейс **ip address**

- Обязательные параметры

  `numbers_ip_address` - номер интерфейса который нужно активировать

### disable ip_address interface mikrotik

Деаткивировать интерфейс **ip address**

- Обязательные параметры

  `numbers_ip_address` - номер интерфейса который нужно деактивировать

### set ip_address interface mikrotik

Изменить конфигурацию интерфейса **ip address**

- Обязательные параметры

  `numbers_ip_address` - номер интерфейса который нужно удалить

  `interface` - интерфейс (например `wlan1`)

  `address` - IP-адрес (например `192.168.88.1\24`)

[comment]: <> (### role)

[comment]: <> (- Обязательные параметры)

[comment]: <> (- Опциональные параметры)

[comment]: <> (### role)

[comment]: <> (- Обязательные параметры)

[comment]: <> (- Опциональные параметры)

[comment]: <> (### role)

[comment]: <> (- Обязательные параметры)

[comment]: <> (- Опциональные параметры)

[comment]: <> (### role)

[comment]: <> (- Обязательные параметры)

[comment]: <> (- Опциональные параметры)

## Cisco

### add ip_address interface cisco

Создать интерфейс **ip address**

- Обязательные параметры

  `interface` - название интерфейса (например `Gig0/2`)
  
  `address` - IP-адрес (например `192.168.88.1\24`)

### remove ip_address interface cisco

Удалить интерфейс **ip address**

- Обязательные параметры

  `interface` - название интерфейса (например `Gig0/2`)

### set ip_address interface cisco

Изменить конфигурацию интерфейса **ip address**

- Обязательные параметры

  `interface` - название интерфейса (например `Gig0/2`)
  
  `address` - IP-адрес (например `192.168.88.1\24`)
