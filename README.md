# 🖥️ Learn Linux Terminal  
> *"Force brain to do something. Please, don’t be lazy."* 💪

Sebuah catatan pribadi untuk **menguasai terminal Linux** — langkah demi langkah, dari dasar hingga mahir.

---

## 📌 Apa Itu CLI (Command Line Interface)?

CLI adalah antarmuka teks yang memungkinkan kamu berinteraksi langsung dengan sistem operasi menggunakan perintah.

### 🔧 Bagaimana CLI Bekerja?
1. Kamu mengetik perintah (misal: `ls`)
2. Shell membaca dan memproses input
3. Sistem mengeksekusi perintah jika valid
4. Hasil (output) ditampilkan di layar

Contoh:
```bash
$ ls
```
Output:
```
Downloads  Documents  Pictures  Projects
```

CLI memberi kendali penuh, efisiensi tinggi, dan merupakan kunci untuk menjadi pengguna Linux yang handal.

> 📚 Sumber utama: [ArchWiki - Core Utilities](https://wiki.archlinux.org/title/Core_utilities)

---

## 🐧 GNU/Linux: Sedikit Gambaran

### 🟦 GNU (GNU’s Not Unix)
- Dibuat oleh **Richard Stallman** sebagai bagian dari proyek GNU untuk menciptakan sistem operasi bebas.
- Menyediakan banyak utilitas penting: kompiler (`gcc`), shell (`bash`), editor (`nano`, `emacs`), dan lainnya.
- Tapi GNU butuh **kernel** untuk berjalan.

### 🟥 Linux (Kernel)
- Dibuat oleh **Linus Torvalds**.
- Linux adalah **kernel** — inti dari sistem operasi.
- Kernel mengelola hardware, memori, proses, dan memberikan layanan ke aplikasi.

### ✅ Jadi, Apa Itu GNU/Linux?
> **GNU + Linux = Sistem Operasi Linux yang kita gunakan.**  
GNU menyediakan tools, Linux menyediakan kernel.

---

## 🧰 Core Utilities (coreutils)

Kumpulan perintah dasar dari proyek GNU yang menjadi tulang punggung sistem Linux. Hampir semua perintah dasar berasal dari `coreutils`.

### 🔤 Perintah Dasar dari Coreutils

| Perintah | Fungsi |
|--------|--------|
| `ls`   | Menampilkan daftar file dan direktori |
| `cd`   | Berpindah direktori (change directory) |
| `pwd`  | Menampilkan lokasi direktori saat ini (print working directory) |
| `mkdir`| Membuat direktori baru |
| `cp`   | Menyalin file atau direktori |
| `mv`   | Memindahkan atau mengganti nama file |
| `rm`   | Menghapus file atau direktori |
| `cat`  | Menampilkan isi file |
| `echo` | Mencetak teks ke terminal |
| `who`  | Menampilkan pengguna yang sedang login |
| `yes`  | Mencetak string terus-menerus (biasanya `y`) |
| `date` | Menampilkan atau mengatur tanggal/waktu |

### 💡 Contoh Penggunaan
```bash
$ mkdir belajar-linux
$ cd belajar-linux
$ echo "Hari ini saya belajar terminal!" > catatan.txt
$ cat catatan.txt
```
Output:
```
Hari ini saya belajar terminal!
```

---

## 🌱 Catatan Ini Akan Terus Berkembang
> Setiap hari sedikit. Setiap minggu lebih baik.  
> Tidak perlu cepat. Tapi **jangan berhenti**.
