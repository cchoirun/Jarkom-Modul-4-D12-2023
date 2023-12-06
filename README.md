# Jarkom-Modul-4-D12-2023

Laporan Resmi Modul Jarkom 4 D12 2023
|Nama|NRP|
|-----|-----|
|Muhammad Revel Wivanto|5025211233|
|Muhammad Choirun Ni'am|5025221203|

Pembagian :
1. Cisco Packet Tracer dengan VLSM - Ni'am
2. GNS 3 dengan CIDR - Revel

## 1. Cisco Packet Tracer dengan VLSM
### 1). Membuat Topologi
Kita akan membuat topologi seperti di soal sebagai berikut : 

<img width="422" alt="1" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/b7a36c30-e116-4c8e-be42-9e3b60b8b216">

Namun perlu diperhatikan beberapa router yang membutuhkan port tambahan sehingga kita perlu menambahkan pada routernya, semisal Aura : 

<img width="345" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/7c19ed33-1a41-40fc-9974-cd54bbaf4ba1">

kita tambahkan dari ```NM-2FE2W```. 
Sedangkan Eisen yang lebih membutuhkan banyak port maka kita ambil dari ```NM-4E``` : 

<img width="343" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/a89cdea6-e0c4-4810-82f4-6eebd0c0250c">

### 2). Subneting

<img width="627" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/29e1b0f1-8782-4af9-97cf-bef27c79d590">

<img width="689" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/6cd57f73-7e51-4f99-883c-b91f88c4439a">

<img width="784" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/819d0ec8-b31e-4b89-8ea9-9a494a2145a5">

<img width="644" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/dac257f3-dd62-4f98-bf1c-07a4d7fb2d4c">

<img width="697" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/1a0fbf18-06fc-4651-8a94-0ff457eb1a84">

<img width="848" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/f0d96158-8f3b-4d14-868d-40cc64b19664">



## 2. GNS 3 Dengan CIDR
### a). Penggabungan IP:
![Screenshot 2023-12-06 095115](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/73584318-260f-4355-8224-5fafea7a1bf5)
![Screenshot 2023-12-06 095211](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/f5ba8cbc-2c2d-4569-a234-92f9b34f95d1)
![Screenshot 2023-12-06 101421](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/d332925a-6342-4244-a4d5-4e884743896e)
![Screenshot 2023-12-06 101613](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/841d9f23-5d84-4825-a79b-1ab3af8712f9)
![Screenshot 2023-12-06 101909](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/88f40c3d-ecf0-42fb-80f8-81d790127c9c)
![Screenshot 2023-12-06 102217](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/f76942ca-12d4-46c3-a730-6e4f91589f51)
![Screenshot 2023-12-06 193016](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/bd479d0e-ce15-4366-a57b-804bb75a0c3e)
-2023/assets/116476269/86e6b26a-8c62-4772-86
![Screenshot 2023-12-06 192840](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/43a6161a-cfea-43fd-93fb-c54254806305)
d9-abe1de941747)
![Screenshot 2023-12-06 193145](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/949c88db-e4c8-42fb-9d48-a9ebdb5a1148)


### b). Tree:
![Modul 4](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/5d63450b-f9f0-4522-979e-3f5cfa26a620)

### c). Pembagian IP:
![Screenshot 2023-12-06 124828](https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/116476269/f028b7fb-2a50-4fbe-8f59-0cb0a79c4703)

### d). Konfigurasi Network:
```
RAura:
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

#A7 
auto eth1
iface eth1 inet static
address 192.197.128.1
netmask 255.255.255.252

#A20 
auto eth2
iface eth2 inet static
address 192.199.1.1
netmask 255.255.255.252

#A9
auto eth3
iface eth3 inet static
address 192.198.144.1
netmask 255.255.255.252

rDenken:
auto lo
iface lo inet loopback

#A20
auto eth0
iface eth0 inet static
address 192.199.1.2
netmask 255.255.255.252
gateway 192.199.1.1

#A21
auto eth1
iface eth1 inet static
address 192.199.0.0
netmask 255.255.255.0

rRoyalcapital:
#A21
auto eth0
iface eth0 inet static
address 192.199.0.3
netmask 255.255.255.0
gateway 192.199.8.1


rWillieRegion:
#A21
auto eth0
iface eth0 inet static
address 192.199.0.5
netmask 255.255.255.0
gateway 192.199.8.1

rFrieren:
auto lo
iface lo inet loopback

#A7
auto eth0
iface eth0 inet static
address 192.197.128.2
netmask 255.255.255.252
gateway 192.197.128.1

#A6
auto eth1
iface eth1 inet static
address 192.197.16.1
netmask 255.255.255.252

#A8
auto eth2
iface eth2 inet static
address 192.197.64.1
netmask 255.255.255.224

rLakeKorridor:
#A8
auto eth0
iface eth0 inet static
address 192.197.64.3
netmask 255.255.255.224
gateway 192.197.64.1

rFlamme:
auto lo
iface lo inet loopback

#A6
auto eth0
iface eth0 inet static
address 192.197.16.3
netmask 255.255.255.252
gateway 192.197.16.1

#A4
auto eth1
iface eth1 inet static
address 192.197.36.9
netmask 255.255.255.252

#A3
auto eth2
iface eth2 inet static
address 192.197.32.1
netmask 255.255.252.0

#A2
auto eth3
iface eth3 inet static
address 192.197.8.1
netmask 255.255.255.248

rFern:
auto lo
iface lo inet loopback

#A2
auto eth0
iface eth0 inet static
address 192.197.8.3
netmask 255.255.255.248
gateway 192.197.8.1

#A1
auto eth1
iface eth1 inet static
address 192.197.0.1
netmask 255.255.248.0

rLaubHills:
#A1
auto eth0
iface eth0 inet static
address 192.197.0.3
netmask 255.255.248.0
gateway 192.197.0.1

rAppetiteRegion:
#A1
auto eth0
iface eth0 inet static
address 192.197.0.5
netmask 255.255.248.0
gateway 192.197.0.1


rRohrRoad:
#A3
auto eth0
iface eth0 inet static
address 192.197.32.3
netmask 255.255.252.0
gateway 192.197.32.1

rHimmel:
auto lo
iface lo inet loopback

#A4
auto eth0
iface eth0 inet static
address 192.197.36.11
netmask 255.255.255.252
gateway 192.197.36.9

#A5
auto eth1
iface eth1 inet static
address 192.197.36.1
netmask 255.255.255.248


rSchewerMountain:
#A5
auto eth0
iface eth0 inet static
address 192.197.36.3
netmask 255.255.255.248
gateway 192.197.36.1

rEisen:
auto lo
iface lo inet loopback

#A9
auto eth0
iface eth0 inet static
address 192.198.144.1
netmask 255.255.255.252
gateway 192.197.144.1

#A10
auto eth1
iface eth1 inet static
address 192.198.64.1
netmask 255.255.255.252

#A16
auto eth2
iface eth2 inet static
address 192.198.144.5
netmask 255.255.255.252

#A17
auto eth3
iface eth3 inet static
address 192.198.136.10
netmask 255.255.255.252

#A11
auto eth4
iface eth4 inet static
address 192.198.32.1
netmask 255.255.255.252

rStark:
#A16
auto eth0
iface eth0 inet static
address 192.198.144.7
netmask 255.255.252.252
gateway 192.198.144.5

rLugner:
auto lo
iface lo inet loopback

#A17
auto eth0
iface eth0 inet static
address 192.198.139.12
gateway 192.198.136.10
netmask 255.255.255.252

#A18
auto eth1
iface eth1 inet static
address 192.198.128.1
netmask 255.255.252.0

#A19
auto eth2
iface eth2 inet static
address 192.198.132.1
netmask 255.255.255.0

rTurkRegion:
#A18
auto eth0
iface eth0 inet static
address 192.198.128.3
netmask 255.255.252.0
gateway 192.198.128.1

rGrobeForest:
#A19
auto eth0
iface eth0 inet static
address 192.198.132.3
netmask 255.255.255.0
gateway 192.198.132.1

rRichter:
#A10
auto eth0
iface eth0 inet static
address 192.198.64.3
netmask 255.255.252.0
gateway 192.198.132.1

rRevolte:
#A10
auto eth0
iface eth0 inet static
address 192.198.64.4
netmask 255.255.252.0
gateway 192.198.132.1

rLinie:
auto lo
iface lo inet loopback

#A11
auto eth0
iface eth0 inet static
address 192.198.32.3
netmask 255.255.255.252
gateway 192.198.32.1

#A12
auto eth1
iface eth1 inet static
address 192.198.16.1
netmask 255.255.254.0

#A13
auto eth2
iface eth2 inet static
address 192.198.8.1
netmask 255.255.255.252


rGranzchannel:
#A12
auto eth0
iface eth0 inet static
address 192.198.16.3
netmask 255.255.254.0
gateway 192.198.16.1

rLawine:
auto lo
iface lo inet loopback

#A13
auto eth0
iface eth0 inet static
address 192.198.8.3
netmask 255.255.255.252
gateway 192.198.8.1

#A14
auto eth1
iface eth1 inet static
address 192.198.4.1
netmask 255.255.255.192

rBredtRegion:
#A14
auto eth0
iface eth0 inet static
address 192.198.4.3
netmask 255.255.255.192
gateway 192.198.4.1

rHeiter:
auto lo
iface lo inet loopback

#A14
auto eth0
iface eth0 inet static
address 192.198.4.5
netmask 255.255.255.192
gateway 192.198.4.1

#A15
auto eth1
iface eth1 inet static
address 192.198.0.1
netmask 255.255.252.0

rSein:
#A15
auto eth0
iface eth0 inet static
address 192.198.0.3
netmask 255.255.252.0
gateway 192.198.0.1

rRiegelCanyon:
#A15
auto eth0
iface eth0 inet static
address 192.198.0.5
netmask 255.255.252.0
gateway 192.198.0.1
```

### e).Routing:
```
ROUTING:

Denken:
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.199.1.1

Lugner:
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.198.136.10

Linie:
up route add -net 192.198.4.0 netmask 255.255.255.192 gw 192.198.8.3
up route add -net 192.198.0.0 netmask 255.255.252.0 gw 192.198.8.3

Lawine:
up route add -net 192.198.0.0 netmask 255.255.252.0 gw 192.198.4.5

Heiter:
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.198.8.3

Himmel:
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.197.16.3

Flamme:
up route add -net 192.197.0.0 netmask 255.255.248.0 gw 192.197.8.3
up route add -net 192.197.36.8 netmask 255.255.255.248 gw 192.197.36.11

Fern:
up route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.197.16.3

Frieren:
up route add -net 192.197.0.0 netmask 255.255.248.0 gw 
192.197.8.3 
up route add -net 192.197.8.0 netmask 255.255.248.0 gw 192.197.16.3
up route add -net 192.197.32.0 netmask 255.255.252.0 gw 192.197.16.3
up route add -net 192.197.36.8 netmask 255.255.252.0 gw 192.197.16.3
up route add -net 192.197.36.0 netmask 255.255.255.248 gw 192.197.36.11

Eisen:
up route add -net 192.198.0.0 netmask 255.255.252.0 gw 192.198.4.3
up route add -net 192.198.4.0 netmask 255.255.255.192 gw 192.198.8.3
up route add -net 192.198.8.0 netmask 255.255.255.252 gw 192.98.32.3
up route add -net 192.198.16.0 netmask 255.255.254.0 gw 192.198.32.3

up route add -net 192.198.128.0 netmask 255.255.252.0 gw 192.198.136.12
up route add -net 192.198.132.0 netmask 255.255.255.0 gw 192.198.136.12

Aura:
# Frieren
up route add -net 192.197.0.0 netmask 255.255.248.0 gw 192.197.8.3
up route add -net 192.197.8.0 netmask 255.255.0.248 gw 192.197.16.3
up route add -net 192.197.32.0 netmask 255.255.252.0 gw 192.197.16.3
up route add -net 192.197.36.8 netmask 255.255.255.252 gw 192.197.16.3
up route add -net 192.197.36.0 netmask 255.255.255.248 gw 192.197.36.11
up route add -net 192.197.16.0 netmask 255.255.255.252 gw 192.197.128.3
up route add -net 192.197.64.0 netmask 255.255.255.224 gw 192.197.128.3


# Denken
up route add -net 192.199.0.0 netmask 255.255.255.0 gw 192.199.1.3

# Eisen
up route add -net 192.198.0.0 netmask 255.255.252.0 gw 192.198.4.3
up route add -net 192.198.4.0 netmask 255.255.255.192 gw 192.198.8.3
up route add -net 192.198.8.0 netmask 255.255.252.252 gw 192.98.32.3
up route add -net 192.198.16.0 netmask 255.255.254.0 gw 192.198.32.3
up route add -net 192.198.32.0 netmask 255.255.255.252 gw 192.198.144.3

up route add -net 192.198.128.0 netmask 255.255.252.0 gw 192.198.136.12
up route add -net 192.198.132.0 netmask 255.255.255.0 gw 192.198.136.12
up route add -net 192.198.136.9 netmask 255.255.255.252 gw 192.198.144.3
up route add -net 192.198.144.4 netmask 255.255.255.252 gw 192.198.144.3

up route add -net 192.198.64.0 netmask 255.255.255.252 gw 192.198.144.3
```