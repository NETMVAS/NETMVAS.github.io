# Interface: Ethernet

## Mikrotik

### enable interface ethernet mikrotik

Активировать **Ethernet-интерфейс**

- Обязательные параметры

    `interface` - название интерфейса    

### disable interface ethernet mikrotik

Активировать **Ethernet-интерфейс**

- Обязательные параметры

    `interface` - название интерфейса   

### config auto-negotiation interface ethernet mikrotik

Включение/отключение автосогласования и задание скорости

- Обязательные параметры

    `interface` - название интерфейса

    `duplex` - состояние интерфейса, активен ли? yes/no в двойных кавычках. (например `"yes"`) 

    `speed` - скорость интерфейса. (например `100Mbps`) 


## Cisco

### enable interface ethernet cisco

Активация **Ethernet** интерфейса

- Обязательные параметры

    `interface` - название интерфейса (например `Gig0/2`)

### disable interface ethernet cisco

Деактивация **Ethernet** интерфейса


- Обязательные параметры

    `interface` - название интерфейса (например `Gig0/2`)

### set interface ethernet cisco

Редактирование параметров **Ethernet** 

- Обязательные параметры

    `interface` - название интерфейса

    `duplex` - состояние интерфейса, активен ли? yes/no в двойных кавычках. (например `"yes"`) 

    `speed` - скорость интерфейса. (например `100Mbps`) 