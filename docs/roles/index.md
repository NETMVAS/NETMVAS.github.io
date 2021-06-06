# Роли (roles)

## Что такое роль?

Роль - ...

## Как устроена роль?

Название ролей имеет следующую конструкцию:

**config_ip_address_interface**, где первая часть название говорит о том, что именно делает роль, всего есть 2 состояния у
роли:

* **config** – конфигурация устройства show – сбор фактов с устройства вторая часть названия говорит о том, с какой функцией
устройства взаимодействует, будь то интерфейсы сетевого устройства, названия, днс или маршрутизация. 

* **show_ip_address** говорит, о том что данная роль соберет факты о состоянии и названии сетевого устройства и выдаст ее.

Третья часть названия говорит, о особенности настройки той или иной единицы

## Описание ролей

|             Роль            |         Краткое описание         | Готовность в % |
|:---------------------------:|:--------------------------------:|:----------------:|
|[config_bandwidth](bandwidth)|Настройка bandwidth|RouterOS: 80%, IOS: 5%|
|[config_capsman](capsman)|Настройка capsman|RouterOS: 80%, IOS: 0%|
|[config_dhcp_client](dhcp_client)|Настройка DHCP-клиента|RouterOS: 100%, IOS: 50%|
|[config_dhcp_server](dhcp_server)|Настройка DHCP-сервера|RouterOS: 100%, IOS: 0%|
|[config_dns](dns)|Настройка DNS|RouterOS: 100%, IOS: 100%|
|[config_hostname](hostname)| Настройка hostname|RouterOS: 100%, IOS: 100%|
|config_interface_bridge     | Настройка интерфейса: bridge     |                |
|config_interface_ethernet   | Настройка интерфейса: ethernet   |                |
|config_interface_ppp_client | Настройка интерфейса: PPP-клиент |                |
|config_interface_ppp_server | Настройка интерфейса: PPP-сервер |                |
|config_interface_vpn        | Настройка интерфейса: VPN        |                |
|config_interface_wireless   | Настройка интерфейса: Wireless   |                |
|config_ip_address_interface | Настройка IP: Address interface  |                |
|config_ip_firewall          | Настройка IP: Firewall           |                |
|config_ip_route             | Настройка IP: Route              |                |
|config_mpls                 | Настройка IP: MPLS               |                |
|config_ntp_client           | Настройка IP: NTP-клиент         |                |
|config_routing_bgp          | Настройка Routing: BGP           |                |
|config_routing_ospf         | Настройка Routing: OSPF          |                |
|config_subinterface         | Настройка Subinterface           |                |
|config_user                 | Работа с правами пользователей   |                |
|config_vlan                 | Настройка VLAN                   |                |
