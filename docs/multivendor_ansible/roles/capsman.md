# CAPsMAN

Роли, настраивающие **CAPsMAN**

## Mikrotik

### add cap interface mikrotik

Добавить CAPsMAN

- Обязательные параметры

  `cap_interface` - название интерфейса

  `mtu` - размер MTU (например `1500`)

- Опциональные параметры

  `arp` - enabled/disabled (по умолчанию `enabled`)

### remove cap interface mikrotik

Удаление CAP

- Обязательные параметры

  `numbers_cap_interface` - номер порта (0-999)

### enable cap interface mikrotik

Активация CAP

- Обязательные параметры

  `numbers_cap_interface` - номер порта (0-999)

### disable cap interface mikrotik

Деактивация CAP

- Обязательные параметры

  `numbers_cap_interface` - номер порта (0-999)

### set cap interface mikrotik

Изменение параметров CAP

- Обязательные параметры

  `numbers_cap_interface` - номер порта (0-999)

  `cap_interface` - название интерфейса

  `mtu` - размер MTU (например `1500`)

- Опциональные параметры

  `arp` - enabled/disabled (по умолчанию `enabled`)

### add caps provisioning mikrotik

Добавить **CAPS provisioning**

- Обязательные параметры

  `rad_mac` - MAC-адрес беспроводного модуля

  `mcfg_name` - какую конфигурацию CAPsMAN привязать к provisioning

- Опциональные параметры

  `action` - действие, на выбор: create-disabled, create-dynamic-enabled, create-enabled, none (по умолчанию `none`)

  `name_format` - на выбор: name_formatcap, identity, prefix, prefix-identity (по умолчанию `cap`)

### remove caps provisioning mikrotik

- Обязательные параметры

  `numbers_caps_provisioning` - номер порта (0-999)

### enable caps provisioning mikrotik

- Обязательные параметры

  `numbers_caps_provisioning` - номер порта (0-999)

### disable caps provisioning mikrotik

- Обязательные параметры

  `numbers_caps_provisioning` - номер порта (0-999)

### set caps provisioning mikrotik

- Обязательные параметры

  `numbers_caps_provisioning` - номер порта (0-999)

  `rad_mac` - MAC-адрес беспроводного модуля

  `mcfg_name` - какую конфигурацию CAPsMAN привязать к provisioning

- Опциональные параметры

  `action` - действие, на выбор: create-disabled, create-dynamic-enabled, create-enabled, none (по умолчанию `none`)

  `name_format` - на выбор: name_formatcap, identity, prefix, prefix-identity (по умолчанию `cap`)

### add caps configuration mikrotik

- Обязательные параметры

  `cfg_name` - название конфигурации

  `ssid` - название сети

- Опциональные параметры

  `mode` - режим (по умолчанию `ap`)

  `hide_ssid` - ssid скрыт? (по умолчанию `no`)

  `distance` - на выбор: indoors, dynamic (по умолчанию `indoors`)

### remove caps configuration mikrotik

Удалить конфигурацию **CAPsMAN**

- Обязательные параметры

  `numbers_caps_configuration` - номер порта (0-999)

### set caps configuration mikrotik

Изменить конфигурацию **CAPsMAN**

- Обязательные параметры

  `numbers_caps_configuration` - номер порта (0-999)

  `cfg_name` - название конфигурации

  `ssid` - название сети

- Опциональные параметры

  `mode` - режим (по умолчанию `ap`)

  `hide_ssid` - ssid скрыт? (по умолчанию `no`)

  `distance` - на выбор: indoors, dynamic (по умолчанию `indoors`)

### add caps channel mikrotik

Добавить канал **CAPsMAN**

- Обязательные параметры

  `channel_name` - название канала

  `frequency` - частота (от 0 до 4294967.29)

  `secondary_frequency` - вторичная частота (от 0 до 4294967.29)

- Опциональные параметры

  `band` - канал. на выбор: 2ghz-b | 2ghz-b/g | 2ghz-b/g/n | 2ghz-onlyg | 2ghz-onlyn | 5ghz-a | 5ghz-a/n | 5ghz-onlyn |
  5ghz-a/n/ac | 5ghz-only-ac (по умолчанию `2ghz-b`)

  `tx_power` - от -30 до 40 (по умолчанию `0`)

### remove caps channel mikrotik

Удалить канал **CAPsMAN**

- Обязательные параметры

  `numbers_caps_channel` - номер порта (0-999)

### set caps channel mikrotik

Редакторить параметры канала **CAPsMAN**

- Обязательные параметры

  `numbers_caps_channel` - номер порта (0-999)
  
  `channel_name` - название канала

  `frequency` - частота (от 0 до 4294967.29)

  `secondary_frequency` - вторичная частота (от 0 до 4294967.29)

- Опциональные параметры

  `band` - канал. на выбор: 2ghz-b | 2ghz-b/g | 2ghz-b/g/n | 2ghz-onlyg | 2ghz-onlyn | 5ghz-a | 5ghz-a/n | 5ghz-onlyn |
  5ghz-a/n/ac | 5ghz-only-ac (по умолчанию `2ghz-b`)

  `tx_power` - от -30 до 40 (по умолчанию `0`)

### add caps datapath mikrotik

Добавить **CAPsMAN Datapath**

- Обязательные параметры

  `datapath_name` - название Datapath

  `mtu` - размер MTU (например `1500`)

  `local_forwarding` - Включить local forwarding? yes или no. 
  *В этом режиме беспроводной интерфейс на CAP ведет себя как обычный интерфейс и участвует в обычной пересылке данных*
  
- Опциональные параметры

  `arp` - enabled/disabled (по умолчанию `disabled`)


### remove caps datapath mikrotik

Удалить **CAPsMAN Datapath**

- Обязательные параметры

  `numbers_caps_configuration` - номер порта (0-999)

### set caps datapath mikrotik

- Обязательные параметры

  `numbers_caps_configuration` - номер порта (0-999)
  
  `datapath_name` - название Datapath

  `mtu` - размер MTU (например `1500`)

  `local_forwarding` - Включить local forwarding? yes или no. 
  *В этом режиме беспроводной интерфейс на CAP ведет себя как обычный интерфейс и участвует в обычной пересылке данных*
  
- Опциональные параметры

  `arp` - enabled/disabled (по умолчанию `disabled`)


### add caps security cfg mikrotik

Добавить конфигурацию безопасности **CAPsMAN**

- Обязательные параметры

  `security_cfg_name` - название конфигурации

  `auth_type` - тип аутентификации. На выбор: wpa-psk|wpa2-psk|wpa-eap|wpa2-eap

  `encryption` - тип шифрования. На выбор: aes-ccm|tkip

  `group_encryption` - тип шифрования группы. тип шифрования. На выбор: aes-ccm|tkip

  `key_update` - время обновления ключа группы (от 30s до 1h)

  `pass` - кодовое слово (от 8 до 63 символов)

### remove caps security cfg mikrotik

Удалить конфигурацию безопасности **CAPsMAN**

- Обязательные параметры

  `numbers_caps_security_cfg` - номер порта (0-999)

### set caps security cfg mikrotik

Изменить данные конфигурации безопасности **CAPsMAN**

- Обязательные параметры

  `numbers_caps_security_cfg` - номер порта (0-999)

### add caps access rule mikrotik

Добавить правило доступа **CAPsMAN**

- Обязательные параметры

  `mac_address` - MAC-адрес

  `mac_mask` - MAC-маска

  `interface` - К какому интерфейсу привязать

  `ssid regexp` - регулярное выражение SSID

  `signal_range` - от -120 до 120

  `time` - ??? always

  `action` - на выбор: accept, query-radius, reject

### remove caps access rule mikrotik

Удалить правило доступа **CAPsMAN**

- Обязательные параметры

  `numbers_caps_access_rule` - номер порта (0-999)

### enable caps access rule mikrotik

Активировать правило доступа **CAPsMAN**

- Обязательные параметры

  `numbers_caps_access_rule` - номер порта (0-999)

### disable caps access rule mikrotik

Деактивировать правило доступа **CAPsMAN**

- Обязательные параметры

  `numbers_caps_access_rule` - номер порта (0-999)

### set caps access rule mikrotik

Изменить данные правила доступа **CAPsMAN**

- Обязательные параметры

  `numbers_caps_access_rule` - номер порта (0-999)

  `mac_address` - MAC-адрес

  `mac_mask` - MAC-маска

  `interface` - К какому интерфейсу привязать

  `ssid regexp` - регулярное выражение SSID

  `signal_range` - от -120 до 120

  `time` - ??? always

  `action` - на выбор: accept, query-radius, reject

### add caps rate mikrotik

Добавить **CAPsMAN** rate

- Обязательные параметры

  `rate_name` - название rate

  `basic_rates` - базовое ограничение. На выбор: 1Mbps|2Mbps|5.5Mbps|11Mbps|6Mbps|9Mbps|12Mbps|18Mbps|24Mbps|36Mbps|48Mbp
s|54Mbps
  
  `sup_rates` - поддерживаемые ограничения. На выбор: На выбор: 1Mbps|2Mbps|5.5Mbps|11Mbps|6Mbps|9Mbps|12Mbps|18Mbps|24Mbps|36Mbps|48Mbp
s|54Mbps

### remove caps rate mikrotik

Удалить **CAPsMAN** rate

- Обязательные параметры

  `numbers_caps_rate` - номер порта (0-999)

### set caps rate mikrotik

Редактировать данные **CAPsMAN** rate

- Обязательные параметры

  `numbers_caps_rate` - номер порта (0-999)

  `rate_name` - название ограничения

  `basic_rates` - базовое ограничение. На выбор: 1Mbps|2Mbps|5.5Mbps|11Mbps|6Mbps|9Mbps|12Mbps|18Mbps|24Mbps|36Mbps|48Mbp
s|54Mbps
  
  `sup_rates` - поддерживаемые ограничения. На выбор: На выбор: 1Mbps|2Mbps|5.5Mbps|11Mbps|6Mbps|9Mbps|12Mbps|18Mbps|24Mbps|36Mbps|48Mbp
s|54Mbps

## Cisco
