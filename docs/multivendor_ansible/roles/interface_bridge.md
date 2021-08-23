# Interface: Bridge

Роли для конфигурации **Bridge**

## Mikrotik

### add bridge mikrotik

Добавить **Bridge**

- Обязательные параметры

    `bridge` - название Bridge

- Опциональные параметры

    `igmp_snooping` - активировать IGMP snooping? yes/no в кавычках (Например `"yes"`, по умолчанию `'no', true`)
    
    `vlan_filtering` - активировать VLAN Filtering? yes/no в кавычках (Например `"yes"`, по умолчанию `'no', true`)
    
### remove bridge mikrotik

Удалить **Bridge**

- Обязательные параметры

  `bridge` -  название Bridge

### enable bridge mikrotik

Активировать **Bridge**

- Обязательные параметры

  `bridge` -  название Bridge

### disable bridge mikrotik

Удалить **Bridge**

- Обязательные параметры

  `bridge` -  название Bridge

### set bridge mikrotik

Редактировать конфигурацию **Bridge**

- Обязательные параметры

  `bridge` -  название Bridge

  `rename_bridge` - новое название Bridge
  
- Опциональные параметры

  `igmp_snooping` - активировать IGMP snooping? yes/no в кавычках (Например `"yes"`, по умолчанию `'no', true`)
    
  `vlan_filtering` - активировать VLAN Filtering? yes/no в кавычках (Например `"yes"`, по умолчанию `'no', true`)


## Cisco

### config ipaddress interface cisco

почему это тут вообще?