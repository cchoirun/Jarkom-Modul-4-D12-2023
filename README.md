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


Terlihat pada gambar terdapat 21 subnet dengan pembagian IP sebagai berikut : 

<img width="472" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/e91463b9-f981-4474-83de-2b2477ec97f5">
<img width="381" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/1ae6da77-2e42-42ff-81ca-a597ccabeca6">

Kemudian dengan tabel tersebut maka kita akan membagikan IP pada masing-masing router,client, dan server sebagai berikut : 
1. Aura :

<img width="472" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/40c0e38b-b2ee-4095-82fb-6878cbfe1214">
  <img width="469" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/0f907e42-d867-4db4-ba81-5a264be440b9">
  <img width="414" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/689fa54c-5a7f-457d-9652-3c3d22819ce5">

3. Denken :

   <img width="431" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/9216225d-ad35-49f3-8a7b-2f49050ab1ef">
   <img width="384" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/38080098-c988-4621-91e2-973a9d60c808">

4. RoyalCapital (client) :

    <img width="276" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/6b0afe75-f587-4de5-8ddf-c5c3f9ecc31d">

5. WilleRegion (client) :

   <img width="277" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/187f67dc-028c-464a-a523-67da2c18954f">

6. Frieren :

   <img width="397" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/ab2e08c7-22a9-4f91-85d6-99a7a6221bb4">
   <img width="387" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/280e2a06-aada-4703-a9c1-a9063f344985">
   <img width="376" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/96d50181-b462-4d65-bed0-fc48b69344e9">

7. Flamme :

    <img width="390" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/dcb31e0c-495a-4042-bb27-9055f0ccf157">
   <img width="337" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/1859fc02-17a9-4ff2-bf36-f5cff90b5700">
   <img width="393" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/3b99bcb5-01ef-44a4-8aec-6df2dcaec1cf">
<img width="353" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/aee65a83-c9e1-4c55-8716-a4dfd7e8b89a">

8. Fern :

   <img width="369" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/e9ccf871-3e9b-402e-89f3-acbbd10d9b3f">
   <img width="347" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/87a7fb18-c1c6-443b-91db-685b18ab482e">

9. laubHills (client):
 
   <img width="269" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/2bdaf611-346c-4ee8-984e-95b6cb767da7">

10. AppetitRegion (client) :

    <img width="245" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/5a50ed1f-e232-483d-b3a8-f5610ac5b656">

11. RohrRoad (client) :

     <img width="244" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/cbd938ca-098d-4563-bb68-9638584c9824">

12. Himmel :

     <img width="375" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/f870ef1a-a048-46c3-a9c2-f863d34b215d">
  <img width="372" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/ca91bc09-6954-4103-8b39-17cb8d80b77b">

13. SchwerMountains :

    <img width="263" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/7d5f0c5c-8427-41db-8218-981d46ebbf74">

14. Eisen :

     <img width="380" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/8e262d78-2972-4ceb-81bc-7775a1051bed">
    <img width="388" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/aa78e20c-888b-4203-b25f-0bcedd383d4b">
    <img width="372" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/ad7c8c29-7955-4c5b-8fbc-add11bb10748">
    <img width="371" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/d77ad922-d986-4212-a173-5fbc2e285cfd">
    <img width="373" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/88453383-ecfc-4e74-90a2-52cd4e943517">

15. Richter (server) :

    <img width="267" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/343fb2ec-391e-4c8e-9636-8dc6f59e4226">

16. Revolte (server) :

     <img width="294" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/afad0e96-9ea5-4793-bdfd-c3e95a9186ae">

17. Stark (Server) :

    <img width="285" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/8fa9f801-3a19-465c-8532-d6eadd36d715">

18. Lugner :

    <img width="396" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/d0c61e2b-aa88-4b67-883c-3c16d4eae4ff">

    <img width="397" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/3e40f11d-c542-463d-93a2-da9674d91631">
    <img width="384" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/8343c621-53d6-4fbd-974b-343ac49553da">

19. TurkRegion (client) :

     <img width="262" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/4ee4c58d-4d84-4b49-9bd7-45de796b4560">
    <img width="268" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/04635b3a-f555-4c3f-af1b-10ba83dea2fe">
    
20. Linie :

    <img width="391" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/31db407f-242d-4674-9fee-e59718e7b945">
    <img width="375" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/9aba5bb7-a5ad-4709-8501-14c1d762e900">
    <img width="387" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/a3258d16-14dd-4295-9e8e-717a097645e8">

21. GranzChannel (client) :

     <img width="273" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/a2b006ae-9def-40b7-9495-2e31040f3619">

22. Lawine :

    <img width="398" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/db17bc27-e59b-4c1b-ac5b-20d5ad84e3e8">
    <img width="404" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/316725e7-60ed-4db4-9103-d24bf7db3b15">

23. BredtRegion (client) :

    <img width="292" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/c2d19db5-d092-405d-baa4-f5a40965c41c">

24. Heiter :

    <img width="400" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/9f3a56c9-07cc-46f4-81d0-9d18b94033cc">
    <img width="374" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/5dd5caf7-7419-4546-aa4d-fc5c1b5abd92">

25. Sein (server) :

     <img width="267" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/ecbd79a4-85de-4a06-a096-2f6a21c561a6">

26. RiegelCanyon (client) :

    <img width="262" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/0333efc0-4cbd-4110-9a8a-7fdd80f3c4c0">

Lalu setelah mengkonfigurasi semua ip, maka kita dapat mengecek apakah subnetting kita berhasil dengan add simple pdu antar subnet : <img width="149" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/d9c77c66-905f-481f-9774-9e305598cc21">

Semisal kita coba antara Denken dengan RoyalCapital : 

<img width="419" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/39738c98-a34f-4d2b-b9fc-74f24ecda0aa">

Dapat dilihat bahwa hasil successfull yang berarti proses subnetting kita berhasil.

### 3). Routing

Tujuan utama dari proses routing adalah untuk dapat menghubungkan device yang berada pada subnet mask lain, semisal kita mencoba mengirim pdu dari RoyalCapital ke Aura: 

<img width="403" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/00af4c02-5244-4e45-a66c-a21ec8499421">

Terlihat bahwa koneksi failed, maka kita perlu melakukan routing seperti yang ada di modul : 

1. Aura :

   <img width="386" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/86380529-1a34-48ff-aa30-2c6d0c72cf22">

3. Denken :

   <img width="280" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/2f1e338f-ba2e-4c8a-a7e9-8f7d16cfb004">

4. Frieren :

   <img width="379" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/423bf705-6ed3-42e3-82c7-5590a08c3f61">

5. Fern :

   <img width="274" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/21ade310-8396-470e-aa18-a187f9a41301">

6. Flamme :
   <img width="301" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/fd99f4a6-1539-4a72-a9ed-8c518e301013">

7. Himmel :
   
   <img width="251" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/3369132b-5d1e-4094-a493-b78a3d65eeea">

8. Eisen :
  
   <img width="282" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/a066b630-9c10-4b01-965b-047e7ed9eb08">


9. Linie:
   
   <img width="249" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/3026d122-38fd-4f77-bcec-ca2f8e4ba80e">

10. Lawine :
    
    <img width="248" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/01034a27-67ed-435f-b2e2-765fa9caaee2">

11. Heiter :
    
    <img width="246" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/733dc7c0-a98d-448d-a40e-1ec433752f2e">

12. Lugner :
    
    <img width="230" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/5985655a-93f8-458d-b205-f52632629727">

Setelah kita konfigurasi masing-masing router, maka kita bisa coba kirim ulang pdu antara beberapa subnet : 

RoyalCapital menuju Aura :

<img width="410" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/3b03697c-e5d8-40b7-8a21-2d15442d6e4e">

Fern menuju Aura :

<img width="392" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/436a91be-ba12-4761-88c1-9490861bcb54">

Aura menuju GranzChannel :

<img width="395" alt="image" src="https://github.com/cchoirun/Jarkom-Modul-4-D12-2023/assets/115228631/da3db8d1-0f24-4dc5-a6f6-35293f8eae76">


Dapat dilihat dari beberapa contoh bahwa kita dapat mengirim pdu antar subnet mask sehingga routing telah berhasil.



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
