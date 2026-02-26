# Minpro1_Pemrograman-Berbasis-Web

# 📌 Website Portofolio

Project ini merupakan website portofolio sederhana yang dibuat menggunakan HTML dan CSS. Website ini terdiri dari beberapa section utama seperti Home (Hero Section), About Me, Skills, dan Certificates.

---

# 🛠️ Teknologi yang Digunakan

* **HTML5** → Untuk struktur halaman website
* **CSS3** → Untuk styling dan layout
* **Bootstrap 5** → Untuk membantu sistem grid & responsive design
* **Vue JS**  → Untuk interaktivitas komponen

---

# 📸 Tampilan Setiap Section / Fitur

## 1️⃣ Home (Hero Section)

![Home Section](assets/home.png)

### 📌 Penjelasan:

Section ini merupakan bagian pertama yang dilihat pengunjung. Biasanya berisi:

* Nama lengkap
* Profesi / status
* Deskripsi singkat
* Tombol Call to Action (contoh: Contact Me)

### 💻 Penjelasan Code:

* Menggunakan tag `<section>` sebagai pembungkus.
* Tag `<h1>` untuk nama.
* Tag `<p>` untuk deskripsi.
* Tombol menggunakan `<a>` atau `<button>`.
* CSS digunakan untuk:

  * Mengatur background
  * Mengatur tinggi section (`height: 100vh;`)
  * Mengatur posisi tengah menggunakan `display: flex;`
  * Memberikan efek hover pada tombol

---

## 2️⃣ About Me

![About Section](assets/about.png)

### 📌 Penjelasan:

Berisi deskripsi lengkap tentang diri, latar belakang pendidikan, dan minat.

### 💻 Penjelasan Code:

* Menggunakan `<section id="about">`
* Layout biasanya menggunakan `display: flex;` atau grid
* Gambar profil menggunakan:

  ```css
  border-radius: 50%;
  object-fit: cover;
  ```
* Teks deskripsi menggunakan `<p>`

---

## 3️⃣ Skills (Progress Bar)

![Skills Section](assets/skills.png)

### 📌 Penjelasan:

Menampilkan kemampuan yang dimiliki dalam bentuk progress bar.

### 💻 Penjelasan Code:

* Setiap skill dibungkus dalam `<div class="skill">`
* Progress bar dibuat dengan:

  ```html
  <div class="progress">
      <div class="progress-bar html"></div>
  </div>
  ```
* CSS digunakan untuk:

  ```css
  .progress {
      background: #ddd;
      height: 10px;
      border-radius: 10px;
  }

  .progress-bar {
      height: 100%;
      background: #4CAF50;
      width: 80%;
  }
  ```
* Lebar (`width`) menunjukkan persentase kemampuan.

---

## 4️⃣ Certificates

![Certificates Section](assets/certificate.png)

### 📌 Penjelasan:

Menampilkan sertifikat yang pernah diperoleh.

### 💻 Penjelasan Code:

* Menggunakan sistem grid atau flexbox
* Setiap sertifikat dibungkus dalam `<div class="card">`
* CSS digunakan untuk:

  * Shadow (`box-shadow`)
  * Hover effect (`transform: scale(1.05);`)
  * Margin & padding

---

# 📂 Struktur Project

```
project-folder/
│
├── index.html
├── style.css
├── assets/
│   ├── home.png
│   ├── about.png
│   ├── skills.png
│   └── certificate.png
└── README.md
```

---

# ⚙️ Cara Menjalankan Project

1. Download atau clone repository
2. Buka folder project
3. Jalankan file `index.html` di browser

---

# 🎯 Tujuan Project

Project ini dibuat untuk:

* Melatih kemampuan HTML & CSS
* Membuat website portofolio sederhana
* Memahami konsep layout, flexbox, dan responsive design

---

# 👤 Author

Nama: (Muhammad Rifqi Jastiartha)
GitHub: https://github.com/arthaa6days

---

⭐ Jika project ini membantu, jangan lupa beri star pada repository ini.
