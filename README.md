Решение экзамена по предмету ОППФКС 3 курс
-
```
Открываем программу через которую мы будем выполнять задание – VMware Workstation:
```
![vmware](/screenshots/Screenshot_1.png)
#### Часть 1 - "Настройка сетевого адаптера для виртуальных машин"
```
1) В программе нажимаем "Edit":
```
![edit](/screenshots/Screenshot_2.png)
```
2) Virtual Network Editor... :
```
![virtual_network_editor](/screenshots/Screenshot_3.png)
```
3) Add Network... :
```
![Add_Network](/screenshots/Screenshot_4.png)
```
4) Выбираем VMnet18 :
```
![VMnat18](/screenshots/Screenshot_5.png)
```
6) OK:
```
![OK1](/screenshots/Screenshot_6.png)
```
7) Вводим подсеть и маску подсети по заданию: 
```
![subnet/mask](/screenshots/Screenshot_7.png)
```
8) DHCP Settings... :
```
![DHCP-settings](/screenshots/Screenshot_8.png)
```
9) Выдаём пул адресов: 
```
![dhcp-pull](/screenshots/Screenshot_9.png)
```
10) OK :
```
![OK2](/screenshots/Screenshot_10.png)
```
11) OK : 
```
![OK3](/screenshots/Screenshot_11.png)

#### Часть 2 - "Создание и настройка виртуальных машин"
"Создание VM DNS"
```
1) "File"
```
![file](/screenshots/Screenshot_12.png)
```
2) New Virtual Machine... : 
```
![newVM](/screenshots/Screenshot_13.png)
```
3) Typical - Next> :
```
![welcomeNVM](/screenshots/Screenshot_14.png)
```
4) Installer disc image file (iso) - Browse... :
```
![image](/screenshots/Screenshot_15.png)
```
5) Подключаем iso файл из сетевой папки по пути:
```
```
\\192.168.202.100\Share302\Материал для экзамена 3 курса по предмету ОППФКС\debian-extended.iso
```
![iso](/screenshots/Screenshot_16.png)
```
6) Open :  
```
![OK4](/screenshots/Screenshot_17.png)
```
7) Next :
```
![next](/screenshots/Screenshot_18.png)
```
8) Называем VM по заданию - Next : 
```
![name](/screenshots/Screenshot_19.png)
```
9) Выдаём ПЗУ по заданию - Next :
```
![disk_size](/screenshots/Screenshot_20.png)
```
10) Customize Hardware... :
```
![customize](/screenshots/Screenshot_21.png)
```
11) Выдаём ОЗУ по заданию :
```
![memory](/screenshots/Screenshot_22.png)
```
12) Выдаём количество ядер и включаем виртуализацию по заданию: 
```
![cpu](/screenshots/Screenshot_23.png)
```
13) Подключаем сетевой адаптер, который мы ранее создали
```
![network](/screenshots/Screenshot_24.png)
```
14) Close :
```
![Close](/screenshots/Screenshot_29.png)
```
15) Finish:
```
![finish](/screenshots/Screenshot_25.png)

"Создание VM balancer1"
```
1) "File"
```
![file](/screenshots/Screenshot_12.png)
```
2) New Virtual Machine... : 
```
![newVM](/screenshots/Screenshot_13.png)
```
3) Typical - Next> :
```
![welcomeNVM](/screenshots/Screenshot_14.png)
```
4) Installer disc image file (iso) - Browse... :
```
![image](/screenshots/Screenshot_15.png)
```
5) Подключаем iso файл из сетевой папки по пути:
```
```
\\192.168.202.100\Share302\Материал для экзамена 3 курса по предмету ОППФКС\debian-extended.iso
```
![iso](/screenshots/Screenshot_16.png)
```
6) Open :  
```
![OK4](/screenshots/Screenshot_17.png)
```
7) Next :
```
![next](/screenshots/Screenshot_18.png)
```
8) Называем VM по заданию - Next : 
```
![nameVM](/screenshots/Screenshot_26.png)
```
9) Выдаём ПЗУ по заданию - Next :
```
![disk_size](/screenshots/Screenshot_20.png)
```
10) Customize Hardware... :
```
![Customize Hardware](/screenshots/Screenshot_27.png)
```
11) Выдаём ОЗУ по заданию :
```
![memory](/screenshots/Screenshot_22.png)
```
12) Выдаём количество ядер и включаем виртуализацию по заданию: 
```
![cpu](/screenshots/Screenshot_23.png)
```
13) Подключаем сетевой адаптер, который мы ранее создали
```
![network](/screenshots/Screenshot_24.png)
```
14) Close :
```
![Close](/screenshots/Screenshot_29.png)
```
15) Finish:
```
![finish](/screenshots/Screenshot_28.png)

"Создание VM balancer2"
```
1) "File"
```
![file](/screenshots/Screenshot_12.png)
```
2) New Virtual Machine... : 
```
![newVM](/screenshots/Screenshot_13.png)
```
3) Typical - Next> :
```
![welcomeNVM](/screenshots/Screenshot_14.png)
```
4) Installer disc image file (iso) - Browse... :
```
![image](/screenshots/Screenshot_15.png)
```
5) Подключаем iso файл из сетевой папки по пути:
```
```
\\192.168.202.100\Share302\Материал для экзамена 3 курса по предмету ОППФКС\debian-extended.iso
```
![iso](/screenshots/Screenshot_16.png)
```
6) Open :  
```
![OK4](/screenshots/Screenshot_17.png)
```
7) Next :
```
![next](/screenshots/Screenshot_18.png)
```
8) Называем VM по заданию - Next : 
```
![name](/screenshots/Screenshot_30.png)
```
9) Выдаём ПЗУ по заданию - Next :
```
![disk_size](/screenshots/Screenshot_20.png)
```
10) Customize Hardware... :
```
![customize](/screenshots/Screenshot_31.png)
```
11) Выдаём ОЗУ по заданию :
```
![memory](/screenshots/Screenshot_22.png)
```
12) Выдаём количество ядер и включаем виртуализацию по заданию: 
```
![cpu](/screenshots/Screenshot_23.png)
```
13) Подключаем сетевой адаптер, который мы ранее создали
```
![network](/screenshots/Screenshot_24.png)
```
14) Close :
```
![Close](/screenshots/Screenshot_29.png)
```
15) Finish :
```
![finish](/screenshots/Screenshot_32.png)

"Создание VM handler"
```
1) "File"
```
![file](/screenshots/Screenshot_12.png)
```
2) New Virtual Machine... : 
```
![newVM](/screenshots/Screenshot_13.png)
```
3) Typical - Next> :
```
![welcomeNVM](/screenshots/Screenshot_14.png)
```
4) Installer disc image file (iso) - Browse... :
```
![image](/screenshots/Screenshot_15.png)
```
5) Подключаем iso файл из сетевой папки по пути:
```
```
\\192.168.202.100\Share302\Материал для экзамена 3 курса по предмету ОППФКС\debian-extended.iso
```
![iso](/screenshots/Screenshot_16.png)
```
6) Open :  
```
![OK4](/screenshots/Screenshot_17.png)
```
7) Next :
```
![next](/screenshots/Screenshot_18.png)
```
8) Называем VM по заданию - Next : 
```
![name](/screenshots/Screenshot_33.png)
```
9) Выдаём ПЗУ по заданию - Next :
```
![disk_size](/screenshots/Screenshot_20.png)
```
10) Customize Hardware... :
```
![customize](/screenshots/Screenshot_34.png)
```
11) Выдаём количество ядер и включаем виртуализацию по заданию: 
```
![cpu](/screenshots/Screenshot_35.png)
```
12) Выдаём количество ядер и включаем виртуализацию по заданию: 
```
![cpu](/screenshots/Screenshot_36.png)
```
13) Подключаем сетевой адаптер, который мы ранее создали
```
![network](/screenshots/Screenshot_37.png)
```
14) Close :
```
![Close](/screenshots/Screenshot_38.png)
```
15) Finish :
```
![finish](/screenshots/Screenshot_39.png)

"Проверка"

+ Проверим название
![vm](/screenshots/Screenshot_40.png)
+ Проверим характеристики
![dns-h](/screenshots/Screenshot_41.png)
![balancer1-h](/screenshots/Screenshot_42.png)
![malancer2-h](/screenshots/Screenshot_43.png)
![handler-h](/screenshots/Screenshot_44.png)

#### Часть 3 - "Установка OC Debian на виртуальные машины"

```
Есть три варианта начальной настройки VM  ()
    1) С помощью графического интерфейса
    2) С помощью обычного – терминального взаимодействия 
    3) С помощью обычного – терминального взаимодействия, но в тёмных тонах ("Dark mode")  

    *** Я буду делать с помощью 3 варианта ****
```
![var](/screenshots/Screenshot_45.png)
```
1) Accessible dark contrast installer menu - Enter :
```
![text](/screenshots/Screenshot_46.png)
```
2) Install - Enter :
```
![install](/screenshots/Screenshot_47.png)
```
3) English - Enter :
```
![eng+enter](/screenshots/Screenshot_48.png)
```
4) United States - Enter :
```
![us+enter](/screenshots/Screenshot_49.png)
```
5) American English - Enter :
```
![american](/screenshots/Screenshot_50.png)
```
6) No - Enter : 
```
![no+enter](/screenshots/Screenshot_51.png)
```
7) Do not configure the network at this time - Enter : 
```
![D+enter](/screenshots/Screenshot_52.png)
```
8) dns/balancer1/balancer2/handler - Continue - Enter :
```
![hostname](/screenshots/Screenshot_53.png)
![hostname](/screenshots/Screenshot_89.png)
![hostname](/screenshots/Screenshot_90.png)
![hostname](/screenshots/Screenshot_91.png)
```
9) toor - Continue - Enter :
```
![password](/screenshots/Screenshot_54.png)
```
10) toor - Continue - Enter :
```
![password](/screenshots/Screenshot_55.png)
```
11) Вводим название новго пользователя по заданию - Continue - Enter :
```
![nuser](/screenshots/Screenshot_56.png)
```
12) Continue - Enter :
```
![nuser](/screenshots/Screenshot_57.png)
```
13) toor - Continue - Enter : 
```
![nupassword](/screenshots/Screenshot_58.png)
```
14) user - Continue - Enter : 
```
![nupassword](/screenshots/Screenshot_59.png)
```
15) Eastern - Enter :
```
![clock](/screenshots/Screenshot_60.png)
```
16) Manual - Enter : 
```
![disk](/screenshots/Screenshot_61.png)
```
17) SCSI3... - Enter :
```
![disk](/screenshots/Screenshot_62.png)
```
18) Yes - Enter :
```
![disk](/screenshots/Screenshot_63.png)
```
19) pci/log 16.1 GB FREE SPACE - Enter:  
```
![disk](/screenshots/Screenshot_64.png)
```
20) Create a new partition - Enter:
```
![disk](/screenshots/Screenshot_65.png)
```
21) 1 GB - Continue - Enter : 
```
![disk](/screenshots/Screenshot_66.png)
```
22) Beginning - Enter :
```
![disk](/screenshots/Screenshot_67.png)
```
23) Изменить значения как показано ниже - Done setting up the partition - Enter : 
```
![disk](/screenshots/Screenshot_68.png)
```
24) Yes - Enter : 
```
![disk](/screenshots/Screenshot_92.png)
```
25) pci/log 15.1 GB FREE SPACE - Enter: 
```
![disk](/screenshots/Screenshot_69.png)
```
26) Create a new partition - Enter:
```
![disk](/screenshots/Screenshot_65.png)
```
27) 2 GB - Continue - Enter :
```
![disk](/screenshots/Screenshot_70.png)
```
28) Logical - Enter :
```
![disk](/screenshots/Screenshot_71.png)
```
29) Beginning - Enter :
```
![disk](/screenshots/Screenshot_72.png)
```
30) Изменить значения как показано ниже - Done setting up the partition - Enter : 
```
![disk](/screenshots/Screenshot_73.png)
```
31) pci/log 13.1 GB FREE SPACE - Enter: 
```
![disk](/screenshots/Screenshot_74.png)
```
32) Create a new partition - Enter:
```
![disk](/screenshots/Screenshot_65.png)
```
33) 6.5 GB - Continue - Enter  :
```
![disk](/screenshots/Screenshot_75.png)
```
34) Logical - Enter : 
```
![disk](/screenshots/Screenshot_76.png)
```
35) Beginning - Enter : 
```
![disk](/screenshots/Screenshot_77.png)
```
36) Изменить значения как показано ниже - Done setting up the partition - Enter : 
```
![disk](/screenshots/Screenshot_78.png)
```
37) pci/log 6.6 GB FREE SPACE - Enter: 
```
![disk](/screenshots/Screenshot_79.png)
```
38) Create a new partition - Enter:
```
![disk](/screenshots/Screenshot_65.png)
```
39) 6.6 GB - Continue - Enter :
```
![disk](/screenshots/Screenshot_80.png)
```
40) Logical - Enter : 
```
![disk](/screenshots/Screenshot_76.png)
```
41) Изменить значения как показано ниже - Done setting up the partition - Enter : 
```
![disk](/screenshots/Screenshot_81.png)
```
42) Finish partitioning and write changes to disk - Enter :
```
![disk](/screenshots/Screenshot_82.png)
```
43) Yes - Enter :
```
![disk](/screenshots/Screenshot_83.png)
```
44) No - Enter :
```
![cpc](/screenshots/Screenshot_84.png)
```
45)
```
```
Для dns/balancer1/balancer2 выбираем standard system utilities - Continue - Enter :  
```
![software](/screenshots/Screenshot_85.png)
```
Для handler выбираем Debian desktop environment
                     Xfce
                     standard system utilities :
```
![s](/screenshots/Screenshot_93.png)
```
46) Yes - Enter :
```
![grub](/screenshots/Screenshot_86.png)
```
47) /dev/sda - Enter : 
```
![grub](/screenshots/Screenshot_87.png)
```
48) Continue - Enter : 
```
![continue](/screenshots/Screenshot_88.png)

"Проверка"
+ dns
![dns](/screenshots/Screenshot_94.png)
+ balancer1
![balancer1](/screenshots/Screenshot_95.png)
+ balancer2
![balancer2](/screenshots/Screenshot_96.png)
+ handler
![handler](/screenshots/Screenshot_97.png)

#### Часть 4 - "Корректирование настроек сетевых адаптеров"
"Работа с сетевыми параметрами на vm dns"
```
1) Логинимся от root :
```
![login](/screenshots/Screenshot_98.png)
```
2) ЛКМ по VM - VM - Removable Devices - CD/DVD(IDE) - Connect :
```
![add](/screenshots/Screenshot_99.png)
```
3) root@dns:~$ apt-cdrom add
    4) root@dns:~$ apt install sudo -y; usermod -aG sudo lapshin339; reboot
        5) Логинимся от user:
```
![add](/screenshots/Screenshot_100.png)
```
6) lapshin339@dns:~$ sudo rm /etc/network/interfaces
    7) lapshin339@dns:~$ sudo apt install network-manager -y
        8) lapshin339@dns:~$ nmtui
            9)Edit a connection - Enter :
```
![nmtui](/screenshots/Screenshot_101.png)
```
10) Wired connection 1 - Enter :
```
![nmtui](/screenshots/Screenshot_102.png)
```
11) Изменить значения как показано ниже - OK :
```
![nmtui](/screenshots/Screenshot_103.png)
```
12) Выходим из nmtui 
    13) lapshin339@dns:~$ sudo reboot
``` 

"Работа с сетевыми параметрами на vm balancer1"
```
1) Логинимся от root :
```
![login](/screenshots/Screenshot_104.png)
```
2) ЛКМ по VM - VM - Removable Devices - CD/DVD(IDE) - Connect :
```
![add](/screenshots/Screenshot_105.png)
```
3) root@balancer1:~$ apt-cdrom add
    4) root@balancer1:~$ apt install sudo -y; usermod -aG sudo lapshin339; reboot
        5) Логинимся от user:
```
![add](/screenshots/Screenshot_110.png)
```
6) lapshin339@balancer1:~$ sudo rm /etc/network/interfaces
    7) lapshin339@balancer1:~$ sudo apt install network-manager -y
        8) lapshin339@balancer1:~$ nmtui
            9)Edit a connection - Enter :
```
![nmtui](/screenshots/Screenshot_101.png)
```
10) Wired connection 1 - Enter :
```
![nmtui](/screenshots/Screenshot_102.png)
```
11) Изменить значения как показано ниже - OK :
```
![nmtui](/screenshots/Screenshot_106.png)
```
12) Выходим из nmtui 
    13) lapshin339@balancer1:~$ sudo reboot
``` 

"Работа с сетевыми параметрами на vm balancer2"
```
1) Логинимся от root :
```
![login](/screenshots/Screenshot_107.png)
```
2) ЛКМ по VM - VM - Removable Devices - CD/DVD(IDE) - Connect :
```
![add](/screenshots/Screenshot_108.png)
```
3) root@balancer2:~$ apt-cdrom add
    4) root@balancer2:~$ apt install sudo -y; usermod -aG sudo lapshin339; reboot
        5) Логинимся от user:
```
![add](/screenshots/Screenshot_109.png)
```
6) lapshin339@balancer2:~$ sudo rm /etc/network/interfaces
    7) lapshin339@balancer2:~$ sudo apt install network-manager -y
        8) lapshin339@balancer2:~$ nmtui
            9)Edit a connection - Enter :
```
![nmtui](/screenshots/Screenshot_101.png)
```
10) Wired connection 1 - Enter :
```
![nmtui](/screenshots/Screenshot_102.png)
```
11) Изменить значения как показано ниже - OK :
```
![nmtui](/screenshots/Screenshot_111.png)
```
12) Выходим из nmtui 
    13) lapshin339@balancer2:~$ sudo reboot
``` 

"Работа с сетевыми параметрами на vm handler"
```
1) Логинимся от root :
```
![login](/screenshots/Screenshot_112.png)
```
2) ЛКМ по VM - VM - Removable Devices - CD/DVD(IDE) - Connect :
```
![add](/screenshots/Screenshot_113.png)
```
3) Ctrl + Alt + T (Откроется терминал)
    4) root@handler:~$ apt-cdrom add
        5) root@handler:~$ apt install sudo -y; usermod -aG sudo lapshin339; reboot
            5) Логинимся от user:
```
![login](/screenshots/Screenshot_114.png)
```
6) Ctrl + Alt + T (Откроется терминал)
    7) lapshin339@handler:~$ sudo rm /etc/network/interfaces
        8) lapshin339@handler:~$ nmtui
            9)Edit a connection - Enter :
```
![nmtui](/screenshots/Screenshot_115.png)
```
10) Wired connection 1 - Enter :
```
![nmtui](/screenshots/Screenshot_116.png)
```
11) Изменить значения как показано ниже - OK :
```
![nmtui](/screenshots/Screenshot_117.png)
```
12) Выходим из nmtui 
    13) lapshin339@handler:~$ sudo reboot
``` 
"Проверка"
+ НА vm dns проверить пинги до всех устройств, включая себя 
![ping](/screenshots/Screenshot_118.png)
+ НА vm handler проверить пинги до всех устройств, включая себя 
![ping](/screenshots/Screenshot_119.png)

#### Часть 5 - "Настройка DNS-сервера"
"Работа настройка dns на vm dns"
```
1) lapshin339@dns:~$ sudo apt install bind9 -y
    2) lapshin339@dns:~$ sudo nano /etc/bind/named.conf.options добавим и изменим несколько строчек :
```
![dns](/screenshots/Screenshot_120.png)
```
3) Ctrl + X
    4) Ctrl + Y
        5) Enter
            6) lapshin339@dns:~$ sudo nano /etc/bind/named.conf.default-zones добавим и изменим несколько строчек :
```
```
zone "lapshin339" {
        type master;
        file "/etc/bind/exam.db"
        allow-transfer { any; };
```
![dns](/screenshots/Screenshot_121.png)
```
7) Ctrl + X
    8) Ctrl + Y
        9) Enter
            10) lapshin339@dns:~$ sudo cp /etc/bind/db.local /etc/bind/exam.db
                11) lapshin339@dns:~$ sudo nano /etc/bind/exam.db добавим и изменим несколько строчек :
```
![dns](/screenshots/Screenshot_122.png)
```
12) lapshin339@dns:~$ sudo reboot
```
"Проверка"
+ НА vm dns ввести команду и проверить работу DNS 
```
 lapshin339@dns:~$ sudo systemctl status bind9
```
![dns](/screenshots/Screenshot_123.png)

+ НА vm handler проверить пинги до всех устройств по доменным именам, включая себя 
![dns](/screenshots/Screenshot_124.png)

#### Часть 6 - "Настройка сервера Samba"
"Настройка сервера samba на vm handler"
```
1) lapshin339@handler:~$ sudo apt install samba -y
    2) lapshin339@handler:~$ sudo nano /etc/samba/smb.conf добавим и изменим несколько строчек :
```
![dns](/screenshots/Screenshot_125.png)
![dns](/screenshots/Screenshot_126.png)
```
3) lapshin339@handler:~$ sudo useradd sambauser
    4) lapshin339@handler:~$ sudo smbpasswd -a sambauser :
```
![samba](/screenshots/Screenshot_127.png)
```
5) lapshin339@handler:~$ sudo mkdir -p /usr/storage
    6) lapshin339@handler:~$ sudo chown sambauser:sambauser /usr/storage/
        7) lapshin339@handler:~$ sudo shutdown now
            8) Примонтируем к VM handler iso образ docker-webapp.iso
                ПКМ по VM - Settings... :
```
![add](/screenshots/Screenshot_128.png)
```
9) Add... :
```
![add](/screenshots/Screenshot_129.png)
```
10) CD/DVD Drive - Finish :
```
![add](/screenshots/Screenshot_130.png)
11) 
```
11) Use ISO image file - Browse... - докидываем файл docker-webapp.iso:
```
![add](/screenshots/Screenshot_131.png)
```
12) OK :
```
![add](/screenshots/Screenshot_132.png)
```
13) Включаем VM 
    14) Логинимся от user:
```
![login](/screenshots/Screenshot_114.png)
```
15) Открываем iso файл docker-webapp
```
![app](/screenshots/Screenshot_133.png)
```
16) Копируем архивы app1.tar и app2.tar на рабочий стол 
    17) Выдаём права Read & Write обоим архивам :
```
![pr](/screenshots/Screenshot_134.png)
```
18) Переносим архивы в директорию /usr/storage/ :
```
![pr](/screenshots/Screenshot_135.png)


#### Часть 7 - "Развертывание контейнеров и настройка балансировщика нагрузки NGINX"

"Работа с контейнерами docker на vm balancer1"
```
1) lapshin339@balancer1:~$ sudo apt install samba-client cifs-utils -y
    2) lapshin339@balancer1:~$ smbclient //handler.lapshin339.exam/public -U sambauser
        3) Вводим пароль:
```
![samba](/screenshots/Screenshot_136.png)
```
4) smb: \> get app1.tar
    5) smb: \> exit
        6) lapshin339@balancer1:~$ sudo apt install docker docker-compose -y
            7) lapshin339@balancer1:~$ sudo docker load < app1.tar
                8)  lapshin339@balancer1:~$ sudo docker run --name app -p 80:80 -d app
```

"Работа с контейнерами docker на vm balancer2"
```
1) lapshin339@balancer2:~$ sudo apt install samba-client cifs-utils -y
    2) lapshin339@balancer2:~$ smbclient //handler.lapshin339.exam/public -U sambauser
        3) Вводим пароль:
```
![samba](/screenshots/Screenshot_137.png)
```
4) smb: \> get app2.tar
    5) smb: \> exit
        6) lapshin339@balancer2:~$ sudo apt install docker docker-compose -y
            7) lapshin339@balancer2:~$ sudo docker load < app1.tar
                8)  lapshin339@balancer2:~$ sudo docker run --name app -p 80:80 -d app
```

"Настройка балансировки nginx на vm handler"
```
1) lapshin339@handler:~$ sudo apt install nginx -y
    2) lapshin339@handler:~$ sudo nano /etc/nginx/sites-available/default изменим структуру файла:
```
```
upstream balancer {
    server balancer1.lapshin339.exam fail_timeout=25;
    server balancer2.lapshin339.exam fail_timeout=25;
}

server {
        listen 80;
        server_name handler.lapshin339.exam;
        index index.html;
        
        location / {
                root /var/www/html;
                proxy_pass http://balancer;
                proxy_set_header Host $host;
                proxy_set_header X-Real-IP $remote_addr;
                proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
        }
}
```
![nginx](/screenshots/Screenshot_138.png)

"Проверка"
+ Заходим в браузер, открываем страничку handler.lapshin339.exam - при выполнении запроса должна отрабатываться балансировка на один из серверов 
![end](/screenshots/Screenshot_139.png)
![end](/screenshots/Screenshot_140.png)
