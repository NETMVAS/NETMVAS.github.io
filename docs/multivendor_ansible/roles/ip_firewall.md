# IP: Firewall

## Mikrotik

## Filter

### add firewall filter mikrotik

Добавить правило **Firewall**

- Обязательные параметры

  `dst_address` - Сопоставляет пакеты, пункт назначения которых равен указанному IP или попадает в указанный диапазон IP

  `dst_port` - Список номеров портов назначения или диапазонов номеров портов

  `src_address` - Сопоставляет пакеты, источник которых равен указанному IP или попадает в указанный диапазон IP.

  `src_port` - Список портов источника и диапазонов портов источника. Применяется, только если протокол TCP или UDP.

  `firewall_action` - действие для правила (например `accept`)

  `chain` - Указывает, к какой цепочке будет добавлено правило. Если входные данные не совпадают с именем уже
  определенной цепи, будет создана новая цепь

  `protocol` - Сопоставляет определенный IP-протокол, указанный именем или номером протокола

### remove firewall filter mikrotik

Удалить правило **Firewall**

- Обязательные параметры

  `ip_firewall_filter` - номер фильтра

### enable firewall filter mikrotik

Активировать правило **Firewall**

- Обязательные параметры

  `ip_firewall_filter` - номер фильтра

### disable firewall filter mikrotik

Деактивировать правило **Firewall**

- Обязательные параметры

  `ip_firewall_filter` - номер фильтра

### set firewall filter mikrotik

Изменить конфигурацию правила **Firewall**

- Обязательные параметры

  `ip_firewall_filter` - номер фильтра

  `dst_address` - Сопоставляет пакеты, пункт назначения которых равен указанному IP или попадает в указанный диапазон IP

  `dst_port` - Список номеров портов назначения или диапазонов номеров портов

  `src_address` - Сопоставляет пакеты, источник которых равен указанному IP или попадает в указанный диапазон IP.

  `src_port` - Список портов источника и диапазонов портов источника. Применяется, только если протокол TCP или UDP.

  `firewall_action` - действие для правила (например `accept`)

  `chain` - Указывает, к какой цепочке будет добавлено правило. Если входные данные не совпадают с именем уже
  определенной цепи, будет создана новая цепь

  `protocol` - Сопоставляет определенный IP-протокол, указанный именем или номером протокола

## NAT

### add firewall nat mikrotik

Добавить **NAT**

- Обязательные параметры

  `dst_address` - Сопоставляет пакеты, пункт назначения которых равен указанному IP или попадает в указанный диапазон IP

  `dst_port` - Список номеров портов назначения или диапазонов номеров портов

  `src_address` - Сопоставляет пакеты, источник которых равен указанному IP или попадает в указанный диапазон IP.

  `src_port` - Список портов источника и диапазонов портов источника. Применяется, только если протокол TCP или UDP.

  `firewall_action` - действие для правила (например `accept`)

  `chain` - Указывает, к какой цепочке будет добавлено правило. Если входные данные не совпадают с именем уже
  определенной цепи, будет создана новая цепь

  `out_interface` - Интерфейс, через который пакет покидает маршрутизатор
  
  `protocol` - Сопоставляет определенный IP-протокол, указанный именем или номером протокола

### remove firewall nat mikrotik

Удалить **NAT**

- Обязательные параметры

  `ip_firewall_nat` - номер фильтра

### enable firewall nat mikrotik

Активировать **NAT**

- Обязательные параметры

  `ip_firewall_nat` - номер фильтра

### disable firewall nat mikrotik

Деактивировать **NAT**

- Обязательные параметры

  `ip_firewall_nat` - номер фильтра

### set firewall nat mikrotik

Изменить конфигурацию **NAT**

- Обязательные параметры

  `ip_firewall_nat` - номер фильтра

## Cisco

### role

    # TODO