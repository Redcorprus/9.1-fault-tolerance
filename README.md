# Домашние задания по модулю  «Отказоустойчивость»

В этом репозитории расположены ваши домашние задания к каждой лекции. 

Обязательны к выполнению задачи без звездочек. Их нужно выполнить, чтобы получить зачёт.

Задачи со звёздочкой (*) — дополнительные задачи или задачи повышенной сложности. Их выполнять не обязательно, но они помогут вам глубже понять тему.

Любые вопросы по решению задач задавайте в чате учебной группы. Ссылку вы найдёте в письме на вашей электронной почте.


1. [Disaster recovery и Keepalived](1.md)

### Задание 1

#### Процесс выполнения:

#### скрин конфигурации первого роутера

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img1.PNG)


#### скрин конфигурации второго роутера

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img2.PNG)


#### проверка работы настроек в CPT

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img3.PNG)


#### ссылка на [схему](hsrp_advancedHW.pkt)



### Задание 2

#### Процесс выполнения:

#### ссылка на [скрипт](nginx.sh)

#### вывод команды ip a на основном сервере

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img4.png)

#### проверка работы keepalived на основном сервере

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img5.png)

#### вывод команды ip a резервном сервере

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img6.png)

#### проверка работы keepalived на резервном сервере

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img7.png)

#### ссылка на [keepalived.conf](keepalived.conf)
------

2. [Кластеризация и балансировка нагрузки](2.md)

### Задание 1

#### Процесс выполнения:

#### ссылка на [конфиг](haproxy.cfg)

#### проверка работы HAProxy 

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img8.png)

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img9.png)


### Задание 2

#### Процесс выполнения:

#### ссылка на [конфиг](haproxy2.cfg)

#### проверка работы HAProxy 

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img10.png)

![alt text](https://github.com/Redcorprus/9.1-fault-tolerance/blob/main/img/img11.png)

3. [Резервное копирование](3.md)

4. [Отказоустойчивость в облаке](4.md)

