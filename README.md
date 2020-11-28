# Jarkom Modul3 Lapres T18
- M. Reza Aisyi 05311840000046
- Agnes Lesmono 05311840000044
---------------------

Untuk soal bisa dilihat di [sini](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/Soal%20Shift%20Modul%203%20DHCP%20dan%20Proxy%20Server.pdf)

## Jawaban

### Nomer 1
Buat topologi seperti gambar berikut (switch ada 3. eth1 switch 1, eth2 switch)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/topologi.sh.PNG)

Setelah dijalankan, edit interfaces di Malang, Mojokerto, Surabaya, dan Tuban

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/1%20etc%20network%20interface%20malang.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/1%20etc%20network%20interface%20mojokerto.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/1%20etc%20network%20interface%20sby.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/1%20etc%20network%20interface%20tuban.PNG)

### Nomer 2
Setup dhcp di Tuban seperti gambar berikut

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/2.1%20setup%20dhcp%20d%20tuban.PNG)

Setup dhcp relay (gunakan isc-dhcp-relay) di Surabaya

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/2.2%20set%20relay%20di%20sby%20(setelah%20install%20isc%20dhcp%20relay).PNG)

Edit ```/etc/dhcp/dhcpd.conf``` di Tuban seperti gambar berikut

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/2.3%20dhcp%20conf%20di%20tuban.PNG)

Cek relay di Surabaya

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/2.4%20sby%20berhasil%20relay.PNG)


### Nomer 3

Setup subnet Tuban untuk client Gresik dan Sidoarjo

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/3.1%20setup%20subnet%20tuban%20client%20gresik%20sidoarjo.PNG)

Edit interface Gresik dan Sidoarjo seperti gambar berikut

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/3.2%20interface%20gresik.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/3.3%20interface%20sidoarjo.PNG)

Hasil subnet Gresik dan Sidoarjo

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/3.4%20hasil%20subnet1%20gresik.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/3.5%20hasil%20subnet1%20sidoarjo.PNG)



### Nomer 4
Setup subnet di Tuban untuk client Banyuwangi dan Madiun

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/4.1%20setup%20subnet%20tuban%20client%20banyuwangi%20madiun.PNG)

Edit interfaces Banyuwangi dan Madiun seperti gambar berikut 

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/4.2%20interface%20banyuwangi.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/4.3%20interface%20madiun.PNG)

Cek sudah bener apa belum

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/4.4%20hasil%20subnet%20madiun.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/4.5%20subnet%20banyuwangi.PNG)

### Nomer 5
Cek DNS di masing-masing client

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/5.1%20dns%20sidoarjo.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/5.2%20dns%20gresik.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/5.3%20dns%20banyuwangi.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/5.4%20dns%20madiun.PNG)


### Nomer 6
Setup waktu untuk peminjaman subnet di ```dhcpd.conf``` di Tuban

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/6.1%20setup%20waktu%20pinjem%20ip%20subnet.PNG)


### Nomer 7
Buat user baru beserta passwordnya

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/7.1%20set%20user%20passwod.PNG)

### Nomer 8 dan 9
Edit sehingga waktu penggunaan sesuai yang diminta di soal

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/8%20dan%209%20set%20waktu%20penggunaan.PNG)


### Nomer 10 
Set supaya bisa redirect seperti gambar berikut (google -> monta)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/10%20redirect.PNG)

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/monta.PNG)

### Nomer 11
Download file yang ada di soal, masukkan ke 
```/usr/share/squid/errors/en```

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/11%201.PNG)

tampilanya seperti ini:

![](https://github.com/Rezaaisyi/Jarkom_Modul3_Lapres_T18/blob/main/img/11.PNG)

### Nomer 12 
Buat seperti bikin domain di modul 2 (tapi belom berhasil :()