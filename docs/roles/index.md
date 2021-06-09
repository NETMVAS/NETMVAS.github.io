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
|[config_hostname](hostname)|Настройка hostname|RouterOS: 100%, IOS: 100%|
|[config_interface_bridge](interface_bridge)|Настройка интерфейса: bridge|RouterOS: 100%, IOS: 0%|
|[config_interface_ethernet](interface_ether)|Настройка интерфейса: ethernet|RouterOS: 100%, IOS: 100%|
|[config_interface_ppp_client](interface_pppclient)|Настройка интерфейса: PPP-клиент |RouterOS: 100%, IOS: 0%|
|[config_interface_ppp_server](interface_pppserver)|Настройка интерфейса: PPP-сервер |RouterOS: 100%, IOS: 0%|
|[config_interface_vpn](interface_vpn)|Настройка интерфейса: VPN|RouterOS: 100%, IOS: 0%|
|[config_interface_wireless](interface_wireless)|Настройка интерфейса: Wireless|RouterOS: 100%, IOS: 0%|
|[config_ip_address_interface](ip_address_interface)|Настройка IP: Address interface  |RouterOS: 100%, IOS: 100%|
|[config_ip_firewall](ip_firewall)|Настройка IP: Firewall|RouterOS: 100%, IOS: 100%|
|[config_ip_route](ip_route)|Настройка IP: Route|RouterOS: 100%, IOS: 100%|
|config_mpls|Настройка IP: MPLS|RouterOS: 100%, IOS: 100%|
|config_ntp_client|Настройка IP: NTP-клиент|RouterOS: 100%, IOS: 100%|
|config_routing_bgp|Настройка Routing: BGP|RouterOS: 100%, IOS: 100%|
|config_routing_ospf|Настройка Routing: OSPF|RouterOS: 100%, IOS: 100%|
|config_subinterface|Настройка Subinterface           |RouterOS: 100%, IOS: 100%|
|config_user|Работа с правами пользователей   |RouterOS: 100%, IOS: 100%|
|config_vlan|Настройка VLAN                   |RouterOS: 100%, IOS: 100%|
