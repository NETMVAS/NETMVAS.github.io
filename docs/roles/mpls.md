# MPLS

## Mikrotik

### add mpls ldp interface mikrotik

- Обязательные параметры

  `interface` - Имя интерфейса, на котором необходимо запустить LDP

  `transport_address` - Используемый транспортный адрес, если он отличается от общих настроек. Если установлено значение
  0.0.0.0, используется транспортный адрес из общих настроек.

- Опциональные параметры

  `dynamic_neighbors` - Определяет, обнаруживать ли соседей динамически или использовать только статически настроенные в
  меню LDP соседи. (yes/no в кавычках, по умолчанию `"yes"`)

  `hello_interval` - Интервал между пакетами hello, которые маршрутизатор посылает через этот интерфейс (по
  умолчанию `5s`)

  `hold_time` - Интервал, после которого сосед объявляется недосягаемым (по умолчанию `15s`)

### remove mpls ldp interface mikrotik

Удалить **MPLS LDP**

- Обязательные параметры

  `numbers_ldp_interface` - название интерфейса

### enable mpls ldp interface mikrotik

Активировать **MPLS LDP**

- Обязательные параметры

  `numbers_ldp_interface` - название интерфейса

### disable mpls ldp interface mikrotik

Деактивировать **MPLS LDP**

- Обязательные параметры

  `numbers_ldp_interface` - название интерфейса

### set mpls ldp interface mikrotik

Изменить конфигурацию **MPLS LDP**

- Обязательные параметры

  `numbers_ldp_interface` - название интерфейса

  `interface` - Имя интерфейса, на котором необходимо запустить LDP

  `transport_address` - Используемый транспортный адрес, если он отличается от общих настроек. Если установлено значение
  0.0.0.0, используется транспортный адрес из общих настроек.

- Опциональные параметры

  `dynamic_neighbors` - Определяет, обнаруживать ли соседей динамически или использовать только статически настроенные в
  меню LDP соседи. (yes/no в кавычках, по умолчанию `"yes"`)

### add mpls ldp neighbor mikrotik

Добавить **MPLS LDP Neighbor**

- Обязательные параметры

  `transport_address` - Транспортный адрес, используемый удаленным "соседом"

- Опциональные параметры

  `send_targeted` - Указывает, отправлять ли целевые сообщения, используемые для целевых (не подключенных напрямую)
  сеансов LDP. yes/no в кавычках (по умолчанию `"yes"`)

### remove mpls ldp neighbor mikrotik

Удалить **MPLS LDP Neighbor**

- Обязательные параметры

  `numbers_ldp_neighbor` - номер соседа

### enable mpls ldp neighbor mikrotik

Активировать **MPLS LDP Neighbor**

- Обязательные параметры

  `numbers_ldp_neighbor` - номер соседа

### disable mpls ldp neighbor mikrotik

Деактивировать **MPLS LDP Neighbor**

- Обязательные параметры

  `numbers_ldp_neighbor` - номер соседа

### set mpls ldp neighbor mikrotik

Изменить параметры **MPLS LDP Neighbor**

- Обязательные параметры

  `numbers_ldp_neighbor` - номер соседа

  `transport_address` - Транспортный адрес, используемый удаленным "соседом"

- Опциональные параметры

  `send_targeted` - Указывает, отправлять ли целевые сообщения, используемые для целевых (не подключенных напрямую)
  сеансов LDP. yes/no в кавычках (по умолчанию `"yes"`)

### set mpls settings mikrotik

- Обязательные параметры

- Опциональные параметры

### set mpls ldp settings mikrotik

- Обязательные параметры

- Опциональные параметры

## Cisco

    TODO