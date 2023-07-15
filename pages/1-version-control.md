---
layout: cover
transition: zoom
---

# Git

---
layout: default
transition: zoom
---

# Git dan Siapa Dia Sebenarnya? 🤔

Git adalah sistem kontrol versi yang memungkinkan kita mengendalikan waktu di kode program kita. Dengan Git, kita bisa melacak perubahan, membandingkan versi kode, dan bahkan kembali ke versi sebelumnya jika perlu. 

---
layout: default
transition: zoom
---

# Mengapa Git Itu Penting? 💡

Pernahkah kamu menulis kode yang sempurna, lalu tanpa sengaja merusaknya dan tidak bisa kembali ke versi sebelumnya? Atau pernahkah kamu bekerja dalam tim dan bingung dengan banyaknya perubahan yang dibuat oleh anggota tim lain? Nah, Git adalah jawaban dari masalah-masalah tersebut.

<v-click>

# Pertanyaan! 🙋‍♀️

Siapa di antara kalian yang pernah mengalami hal tersebut? Bagaimana perasaanmu saat itu?

</v-click>

---
layout: default
transition: zoom
---

# Instalasi Git 🛠

Untuk menggunakan Git, kita harus menginstalnya terlebih dahulu. Cara menginstalnya bergantung pada sistem operasi yang kamu gunakan.

<v-click>

## Windows

Download installer Git dari [sini](https://git-scm.com/download/win) dan jalankan seperti biasa.

</v-click>

<v-click>

## MacOS

Gunakan Homebrew dan jalankan perintah `brew install git` di Terminal.

</v-click>

<v-click>

## Linux

Jalankan perintah `sudo apt-get install git` di Terminal.

</v-click>


---
layout: default
transition: zoom
---

# Beberapa Konsep Dasar Git 👀

Ada beberapa konsep penting yang perlu kita ketahui tentang Git, yaitu: Repository, Commit, Branch, dan Merge. Mari kita pelajari satu per satu.

---
layout: default
transition: zoom
---

# Repository 💼

Repository adalah tempat di mana Git menyimpan semua perubahan dan riwayat kode. Kamu bisa membayangkannya sebagai database untuk kode mu.

<v-click>

## Membuat Repository Baru

```sh
git init
```

Perintah ini akan membuat repository Git baru di direktori saat ini.

</v-click>

---
layout: default
transition: zoom
---

# Commit 📝

Commit adalah "snapshot" atau gambaran dari perubahan kode kita. Setiap kali kita membuat perubahan dan ingin menyimpannya, kita membuat commit.

<v-click>

## Membuat Commit

```sh
git commit -m "Pesan commit"
```

Terdapat [convention](https://www.conventionalcommits.org/en/v1.0.0/) untuk pesan commit, yaitu:
- `feat`: fitur baru / perubahan UI
- `fix`: perbaikan bug
- `docs`: dokumentasi
- `style`: perubahan yang tidak mempengaruhi kode (format, dll)
- `refactor`: perubahan kode yang tidak memperbaiki bug atau menambah fitur
- `chore`: perubahan pada build system, konfigurasi, dll

```sh
git commit -m "feat: tampilan halaman login"
```

</v-click>

---
layout: default
transition: zoom
---

# Branch dan Merge 🌳

Branch memungkinkan kita membuat salinan kode untuk bekerja tanpa mengganggu kode utama. Setelah selesai, kita bisa menggabungkan (Merge) perubahan kita ke kode utama.

<v-click>

## Membuat Branch Baru

```sh
git branch nama-branch
git checkout nama-branch
# atau
git checkout -b nama-branch
```

</v-click>

<v-click>

## Menggabungkan Branch

```sh
git commit -m "Pesan commit"
```

Perintah ini akan menggabungkan perubahan di branch tersebut ke branch yang saat ini aktif.

</v-click>

---
layout: default
transition: zoom
---

# GitHub - Kolaborasi Tanpa Batas 🌐

Jika Git adalah alat, maka GitHub adalah ruang kerja digital Anda. GitHub adalah platform pengembangan perangkat lunak yang memungkinkan jutaan pengembang berkolaborasi.

<v-click>

GitHub mengubah proses kerja dalam tim menjadi lebih transparan dan fleksibel. Fitur seperti Pull Requests, Issues, dan Actions membantu kita mengelola proyek dengan efisien. 

Dan tahu apa yang lebih keren? GitHub tidak hanya tentang kode, tapi juga tentang orang-orang dan komunitas. Mari bersama-sama membangun sesuatu yang luar biasa!

</v-click>

---
