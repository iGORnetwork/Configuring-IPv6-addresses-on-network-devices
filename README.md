# Configuring-IPv6-addresses-on-network-devices
## Базавая настройка S1
![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_1.png)
![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_2.png)
# Базавая настройка R1
![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_3.png)
![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_4.png)
# Назначим IPv6-адреса интерфейсам Ethernet на R1.
1. Включаем интерфесы 0/0 ; 0/1 

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_5.png)

2. Включаем ipV6 на интерфейсах 0/0 ; 0/1 

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_6.png)

3. Устанавливаем ip addres link local

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_7.png)

4. Устанавливаем глобальных адреса IPv6

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_11.png)

# Активируем IPv6-маршрутизацию на R1

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_8.png)
![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_9.png)

# Назначим IPv6-адреса интерфейсу S1.

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_10.png)

# Проверка сквозного подключения

1) С PC-A отправляем эхо-запрос на R1 FE80::1

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_12.png)

2) С PC-A отправляем эхо-запрос на S1 2001:db8:acad:1::b S1

![](https://github.com/iGORnetwork/Configuring-IPv6-addresses-on-network-devices/blob/main/image/Screenshot_14.png)






