# role

## Mikrotik

## PPPoE

### add pppoe server mikrotik

Создать **PPPoE** сервер

- Обязательные параметры

    `pppoe_server` - название PPPoE сервера

    `interface` - интерфейс, к которому будет привязан PPPoE сервер (например `ether2`) 
  
    `ppp_profile` - PPP профиль (например `profile1`, если такой создан)

    `authentication` - профили безопасности (например `mcshap1,mschap2,chap,pap`)

### remove pppoe server mikrotik

Удалить **PPPoE** сервер

- Обязательные параметры

    `numbers_pppoe_server` - номер PPPoE-сервера (0-999)

### enable pppoe server mikrotik

Активировать **PPPoE** сервер

- Обязательные параметры

    `numbers_pppoe_server` - номер PPPoE-сервера (0-999)

### disable pppoe server mikrotik

Деактивировать **PPPoE** сервер

- Обязательные параметры

    `numbers_pppoe_server` - номер PPPoE-сервера (0-999)

### set pppoe server  mikrotik

Измернить конфигурацию **PPPoE** Сервера

- Обязательные параметры

    `numbers_pppoe_server` - номер PPPoE-сервера (0-999)

    `rename_pppoe_server` - название PPPoE сервера

    `interface` - интерфейс, к которому будет привязан PPPoE сервер (например `ether2`) 
  
    `ppp_profile` - PPP профиль (например `profile1`, если такой создан)

    `authentication` - профили безопасности (например `mcshap1,mschap2,chap,pap`)


## L2TP

### enable l2tp server mikrotik

Активировать **L2TP** сервер. Параметры передавать не требуется.

### disable l2tp server mikrotik

Деактивировать **L2TP** сервер. Параметры передавать не требуется.

### set l2tp server mikrotik

Изменить конфигурацию **L2TP** сервера.

- Обязательные параметры

  `ppp_profile` - PPP профиль (например `profile1`, если такой создан)

  `authentication` - профили безопасности (например `mcshap1,mschap2,chap,pap`)

  `one_session` - возможно ли подключение клиента с одного хоста? yes/no в двойных кавычках (например `"yes"`)

## SSTP

### enable sstp server mikrotik

Активация **SSTP** сервера. Параметры передавать не требуется.

### disable sstp server mikrotik

Деактивация **SSTP** сервера. Параметры передавать не требуется.

### set sstp server mikrotik

Изменение конфигурации **SSTP** Сервера

- Обязательные параметры

  `ppp_profile` - PPP профиль (например `profile1`, если такой создан)
  
  `authentication` - профили безопасности (например `mcshap1,mschap2,chap,pap`)

## PPTP

### enable pptp server mikrotik

Активация **SSTP** сервера. Параметры передавать не требуется.


### disable pptp server mikrotik

Деактивация **PPTP** сервера. Параметры передавать не требуется.


### set pptp server mikrotik

Изменение конфигурации **PPTP** сервера.

- Обязательные параметры

  `ppp_profile` - PPP профиль (например `profile1`, если такой создан)

  `authentication` - профили безопасности (например `mcshap1,mschap2,chap,pap`)


## PPP

### add ppp server mikrotik

Создание **PPP** сервера

- Обязательные параметры

  `ppp_server` - Название PPP сервера

  `ppp_profile` - PPP профиль (например `profile1`, если такой создан)

  `authentication` - профили безопасности (например `mcshap1,mschap2,chap,pap`)


### remove ppp server mikrotik

Удалить **PPP** сервер

- Обязательные параметры

  `numbers_ppp_server` - Номер PPP сервера

### enable ppp server mikrotik

Активировать **PPP** сервер

- Обязательные параметры

  `numbers_ppp_server` - Номер PPP сервера

### disable ppp server mikrotik

Деактивировать **PPP** сервер

- Обязательные параметры

  `numbers_ppp_server` - Номер PPP сервера

### set ppp server mikrotik

Изменить конфигурацию **PPP** сервера

- Обязательные параметры

  `numbers_ppp_server` - Номер PPP сервера

  `rename_ppp_server` - Название PPP сервера

  `interface` - название интерфейса, который будет привязан к PPP серверу

  `ppp_profile` - PPP профиль (например `profile1`, если такой создан)

  `authentication` - профили безопасности (например `mcshap1,mschap2,chap,pap`)


### add ppp profile mikrotik

Создать профиль **PPP**

- Обязательные параметры

  `ppp_profile` - название PPP профиля

  `bridge` - bridge на который будет привязан PPP сервер

  `local_address` - Адрес туннеля или имя пула, из которого адрес назначается интерфейсу ppp локально

  `remote_address` - Адрес туннеля или имя пула, из которого назначается адрес удаленному ppp-интерфейсу

  `dns_server` - адрес DNS сервера (например `1.1.1.1`)

### remove ppp profile mikrotik

Удалить **PPP** профиля

- Обязательные параметры

  `ppp_profile` - название PPP профиля

### set ppp profile mikrotik

Изменить параметры **PPP** профиля

- Обязательные параметры

  `ppp_profile` - название PPP профиля
  
  `bridge` - bridge на который будет привязан PPP сервер

  `local_address` - Адрес туннеля или имя пула, из которого адрес назначается интерфейсу ppp локально

  `remote_address` - Адрес туннеля или имя пула, из которого назначается адрес удаленному ppp-интерфейсу

  `dns_server` - адрес DNS сервера (например `1.1.1.1`)


### add ppp secret mikrotik

Создать **PPP** секрет 

- Обязательные параметры

  `username` - имя используемое для входа

  `password` - пароль используемый для входа

  `local_address` - IP-адрес, который будет установлен локально на PPP интерфейсе

  `remote_address` - IP-адрес, который будет присвоен удаленному интерфейсу PPP

  `ppp_profile` - какой [user_profile](https://wiki.mikrotik.com/wiki/Manual:PPP_AAA#User_profiles) использовать

### remove ppp secret mikrotik

Удалить **PPP** секрет 

- Обязательные параметры

  `username` - имя используемое для входа (по нему ищется PPP секрет)

### enable ppp secret mikrotik

Активировать **PPP** секрет

- Обязательные параметры

  `username` - имя используемое для входа (по нему ищется PPP секрет)

### disable ppp secret mikrotik

Деактивировать **PPP** секрет 

- Обязательные параметры

  `username` - имя используемое для входа (по нему ищется PPP секрет)

### set ppp secret mikrotik

Изменить параметры **PPP** секрета 

- Обязательные параметры

  `username` - имя используемое для входа (по нему ищется PPP секрет)

  `rename_username` - новое имя пользователя

  `password` - пароль используемый для входа

  `local_address` - IP-адрес, который будет установлен локально на PPP интерфейсе

  `remote_address` - IP-адрес, который будет присвоен удаленному интерфейсу PPP

  `ppp_profile` - какой [user_profile](https://wiki.mikrotik.com/wiki/Manual:PPP_AAA#User_profiles) использовать

## Cisco

### role

- Обязательные параметры

- Опциональные параметры