# Mencoba Linux untuk Pertama Kali

## P, Paket

Linux itu operating system yang serba online, jadi beda sama windows, tiap aplikasi (bahkan yang krusial kayak audio, device, driver) itu selalu update di linux, dan kewajibanmu adalah update, biar OS mu ga outdated dan gampang kena hek.

**Debian** merupakan distro (jenis linux) yang tergolong mudah dalam melakukan ini, program manajemen paketnya disebut ***apt***.

Sumber pustaka **Debian** yang menjadi *mekah* dan pusatnya disebut repository, dan library, aplikasi, program, kita sebut ***package***(paket).

Berbeda dengan ~~jendela~~ Windows, kita ga nyari *exe* atau download klik2 dari internet, kita hanya perlu mengetik:

```bash
sudo apt install <nama aplikasi>
```

kecuali klo ga tersedia di *repository* itulah kenapa jenis distro yang kita pilih (Debian) itu mempengaruhi kekayaan/ketersediaan paket.

menarik bukan? atau mendorong?

***Linux*** mengajarkan mu untuk nyaman *mengetik* dan orientasinya memang *keyboard only*, kenapa?

## Keyboard-Only Workflows

Menggunakan ***Mouse*** terlalu lama dan berlebihan dapat mengakibatkan **Repititive Strain Injuries (RSI)** atau disebut **Carpal Tunnel Syndrome** dan **Mouse Arm (Mouse Syndrome)** juga **Neck Strain** atau sakit bahu kanan, maka kelebihan menggunakan keyboard saja dapat:

* Mengurangi gejala dan penyakit diatas
* Kecepatan mengetik dan navigasi
* (***Flow State***) Fokus/Konsentrasi yang tidak terganggu

Hal-hal tersebut dapat mempengaruhi produktifitas.

## Repository

```
Repository = katalog software + gudang paket
```

ketika kita mengetik:

```bash
sudo apt install git
```

`apt` akan mencari paket nya berdasarkan target repo yang ada di sistem kita, kamu bisa liat di:

```bash
ls /etc/apt/sources.list.d/
```

Disitu berisi alamat-alamat website gudang kita

## Dependency

Nah ini menarik, banyak perangkat lunak butuh perangkat lunak lain untuk dapat berjalan dengan baik.

Package manager seperti **apt** membantu mengelola dependency supaya tidak kacau dan penuh error.

## Apt


