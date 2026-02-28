# 🌐 Portfolio Website  
## Grace Vies Angel – Sistem Informasi  

---

## 📌 Deskripsi Project

Website ini merupakan project portfolio pribadi yang saya buat sebagai bagian dari tugas mata kuliah Pemrograman Berbasis Web. Website ini berisi informasi mengenai diri saya, mulai dari perkenalan singkat, kemampuan yang saya miliki, pengalaman organisasi, hingga sertifikat yang pernah saya peroleh. Tujuan dari pembuatan website ini untuk menampilkan profil diri dalam bentuk website yang terstruktur dan responsif.

Dalam proses pembuatannya, saya menggunakan HTML sebagai struktur utama halaman, CSS untuk mengatur tampilan visual, Bootstrap 5 untuk membantu pengaturan layout agar responsif, serta Vue JS untuk menampilkan beberapa data seperti skills dan sertifikat secara lebih terstruktur.

---

## 🎨 Tampilan Setiap Section

### 🏠 Home (Hero Section)

Bagian Home merupakan tampilan pertama yang muncul ketika website dibuka. Pada bagian ini saya menampilkan nama lengkap, bidang yang saya tekuni yaitu *Creative Design & Management*, serta deskripsi singkat mengenai minat saya di bidang desain dan manajemen diri. Layout pada section ini dibagi menjadi dua kolom. Kolom sebelah kiri berisi teks perkenalan, sedangkan kolom sebelah kanan menampilkan foto profil. Saya menggunakan ukuran font yang cukup besar pada bagian nama agar langsung menjadi fokus utama saat halaman pertama kali dibuka.

<img width="1897" height="908" alt="image" src="https://github.com/user-attachments/assets/17952ac0-4d0b-4a64-bd5d-ca9e04e73bb5" />


---

### 👤 About Me

Pada bagian Section About Me berisi informasi yang lebih lengkap mengenai diri saya. Bagian ini dibagi menjadi tiga card utama dalam satu baris, yaitu Deskripsi Diri, Skills, dan Pengalaman. Pada bagian Deskripsi Diri, saya menjelaskan latar belakang saya sebagai mahasiswa Sistem Informasi serta minat saya dalam pengelolaan organisasi dan pengembangan kreativitas digital. Bagian Skills menampilkan daftar kemampuan dalam bentuk progress bar. Saya memilih menggunakan progress bar agar tingkat kemampuan dapat terlihat secara visual dan lebih mudah dipahami. Bagian Pengalaman berisi daftar kegiatan dan kontribusi yang pernah saya lakukan, khususnya dalam organisasi kampus. Informasi ditampilkan dalam bentuk poin agar lebih ringkas dan mudah dibaca.

<img width="1893" height="882" alt="image" src="https://github.com/user-attachments/assets/e60d64e7-f43a-4e6e-9014-94f375c7693c" />


---

### 🏆 Certificates

Section Certificates menampilkan daftar sertifikat yang pernah saya peroleh. Setiap sertifikat ditampilkan dalam bentuk card yang berisi gambar, tahun, dan judul kegiatan. Saya menambahkan tombol “Detail” pada setiap sertifikat. Ketika tombol tersebut diklik, akan muncul modal yang menampilkan gambar sertifikat dalam ukuran lebih besar. Jadi, pengunjung dapat melihat detail sertifikat tanpa harus berpindah halaman. Pada Section ini berfungsi sebagai bukti pencapaian dan pengalaman yang telah saya peroleh selama perkuliahan.

<img width="1899" height="862" alt="image" src="https://github.com/user-attachments/assets/a2208717-4ee3-47ab-81a5-c2183e09329a" />

<img width="1900" height="877" alt="image" src="https://github.com/user-attachments/assets/1330ebfc-6ff1-4d0f-8d10-e75568daffb2" />


---

## Penjelasan Code Setiap Section

### 🔹 Struktur Dasar HTML

Website ini diawali dengan struktur dasar HTML seperti berikut:
Bagian ini berfungsi sebagai kerangka utama halaman website. Meta viewport digunakan agar tampilan bisa menyesuaikan ukuran layar perangkat.

<img width="719" height="164" alt="image" src="https://github.com/user-attachments/assets/13f8150b-7d02-48ae-a172-ee3e0e9f4de0" />


### 🔹 Section Home

### > Kode Section Home (Hero Section)

<img width="801" height="579" alt="image" src="https://github.com/user-attachments/assets/1a872c08-45c8-4430-b456-79f31ca3e7f7" />

Penjelasan :

* Pada bagian Home ini, saya membuat satu section utama dengan id home supaya bisa terhubung langsung dengan menu navigasi di atas. Jadi ketika tombol “Home” diklik, halaman akan langsung scroll ke bagian ini tanpa perlu pindah halaman. Struktur layout-nya saya bagi menjadi dua kolom menggunakan sistem grid dari Bootstrap. Kolom pertama berisi teks seperti nama, role, dan deskripsi singkat tentang diri saya. Sedangkan kolom kedua digunakan untuk menampilkan foto profil. Dengan pembagian seperti ini, tampilan terlihat lebih seimbang antara teks dan gambar. Saya juga menggunakan class container dan row agar isi konten tetap rapi dan menyesuaikan ukuran layar. Kalau dibuka di laptop tampil berdampingan, tapi kalau di HP otomatis menjadi satu kolom. Jadi tampilannya tetap nyaman dilihat di berbagai perangkat.

---

<img width="502" height="61" alt="image" src="https://github.com/user-attachments/assets/95a9aff6-c101-4161-8b39-3d36884785d6" />

Penjelasan :

* Pada bagian ini saya menggunakan class `container` agar isi konten tidak terlalu melebar ke pinggir layar. Kemudian `row` digunakan untuk membuat satu baris layout sebelum dibagi menjadi kolom.

---

<img width="755" height="272" alt="image" src="https://github.com/user-attachments/assets/3165adb5-aa2b-439f-98d4-0b014a325674" />

Penjelasan :

* Pada bagian ini saya membuat kolom pertama menggunakan col-lg-6, supaya di layar besar tampil setengah layar. Isi kolom ini adalah nama, role, dan deskripsi singkat tentang diri saya. Tag h1 digunakan untuk menampilkan nama sebagai judul utama. Bagian {{ name }} saya pakai karena menggunakan Vue, jadi namanya bisa diatur dari data. Lalu h2 untuk menampilkan bidang yang saya tekuni. Sedangkan p berisi deskripsi singkat, dan class yang digunakan mengatur ukuran serta jarak teks supaya enak dibaca.


---

<img width="602" height="142" alt="image" src="https://github.com/user-attachments/assets/41a08e0a-80aa-4fde-b478-1a87bdee5d6f" />

Penjelasan:

* Disini saya juga memakai col-lg-6, supaya sejajar dengan kolom teks di layar besar. Class text-center dipakai agar foto berada di tengah, dan juga foto pdh saya memakai <div class="image-wrapper"> supaya bisa diberi styling seperti background, bayangan, dan efek hover lewat CSS. Lalu tag <img> digunakan untuk menampilkan gambar profil, dengan img-fluid agar ukurannya tetap responsif mengikuti layar.

---

### > Styling Hero Section (CSS)

1️⃣ CSS .hero-section


<img width="253" height="114" alt="image" src="https://github.com/user-attachments/assets/c2510d68-c275-42b7-8f30-5d348956d4f9" />


Penjelasan :

* Class .hero-section saya gunakan untuk mengatur jarak atas dan bawah pada bagian Home. Saya menambahkan padding-top dan padding-bottom agar konten tidak terlalu mepet dengan navbar di atas maupun section berikutnya di bawah. Dengan jarak ini, tampilan Hero terlihat lebih lega dan nyaman dilihat.

---

2️⃣ CSS .hero-title

<img width="358" height="179" alt="image" src="https://github.com/user-attachments/assets/036955a3-b9e9-4d71-99a6-cf3eaf930755" />

Penjelasan :

* Class .hero-title digunakan untuk mengatur tampilan nama pada bagian Hero. Saya memperbesar ukuran font agar menjadi fokus utama saat halaman dibuka. font-weight: 900 membuat teks terlihat tebal dan kuat. Warna biru dipilih agar sesuai dengan tema website. Properti text-shadow saya tambahkan untuk memberi efek bayangan sehingga teks terlihat lebih menarik dan tidak terlalu datar.

---

3️⃣ CSS .hero-role

<img width="226" height="179" alt="image" src="https://github.com/user-attachments/assets/1385138d-fd15-4d05-be57-84514713e4d5" />


Penjelasan :

* Class .hero-role digunakan untuk menampilkan role atau bidang yang saya tekuni. Ukurannya lebih kecil dari nama agar tetap menjadi informasi pendukung. Warna dibuat sedikit lebih terang supaya tetap selaras dengan tema. Saya juga menggunakan text-align: center agar teks berada di tengah dan terlihat seimbang dengan elemen lainnya.

---

4️⃣ CSS .hero-desc

<img width="230" height="178" alt="image" src="https://github.com/user-attachments/assets/d6babb4a-df46-430a-a8e9-540bc83cb811" />


Penjelasan :

* Class .hero-desc digunakan untuk paragraf deskripsi singkat. Saya membatasi lebar teks dengan max-width agar tidak terlalu panjang ke samping sehingga lebih mudah dibaca. line-height saya atur supaya jarak antar baris lebih nyaman dilihat. Posisi teks dibuat rata tengah agar tampilannya lebih rapi dan seimbang dengan judul di atasnya.

---

### > Kode Tampilan Foto (Hero Image Styling – CSS)

<img width="447" height="346" alt="image" src="https://github.com/user-attachments/assets/10f18a26-ea18-4fc9-9d30-d51ba3f23e9e" />

Penjelasan :

* Pada bagian ini saya membuat wadah atau frame untuk foto profil menggunakan class .image-wrapper. Saya mengatur ukuran tetap 350px agar bentuknya konsisten dan tidak berubah-ubah. Warna background biru digunakan supaya selaras dengan tema website. Saya menggunakan display: flex agar posisi gambar berada di tengah secara horizontal dan berada di bagian bawah frame. Properti box-shadow saya tambahkan untuk memberi efek bayangan sehingga tampilannya tidak terlihat datar. Kemudian overflow: hidden digunakan supaya bagian gambar yang keluar dari frame tidak terlihat.

---

<img width="357" height="321" alt="image" src="https://github.com/user-attachments/assets/2e00c9d3-388b-4d3e-9002-67598db31ee4" />

Penjelasan :

* Bagian ini saya gunakan untuk membuat efek cahaya di belakang foto. Elemen ::before adalah pseudo-element yang berfungsi sebagai dekorasi tambahan tanpa harus menambah elemen HTML baru. Saya menggunakan radial-gradient dengan warna putih transparan agar terlihat seperti pantulan cahaya. Efek blur ditambahkan supaya tampilannya lebih halus dan tidak terlalu tajam. Tujuannya agar foto terlihat lebih hidup dan tidak kaku.

---

<img width="383" height="349" alt="image" src="https://github.com/user-attachments/assets/ccdc3a36-cb99-4939-8c4e-9bd5a9dc3c8c" />

Penjelasan :

* Pada bagian ::after, saya menambahkan efek gradasi di bagian bawah foto. Gradasi ini dibuat menggunakan linear-gradient agar bagian bawah gambar terlihat menyatu dengan background. Efek ini juga membantu memberikan kesan transisi yang lebih halus antara foto dan frame. Properti pointer-events: none digunakan agar elemen dekoratif ini tidak mengganggu interaksi pengguna.

---

<img width="430" height="178" alt="image" src="https://github.com/user-attachments/assets/dabd96f4-6bbf-4b9f-8760-2771e3977327" />

Penjelasan : 
* Pada bagian ini saya menambahkan efek ketika kursor diarahkan ke foto. Gambar akan sedikit terangkat dan membesar menggunakan transform, sehingga terlihat lebih interaktif. Selain itu, bayangan pada frame juga menjadi sedikit lebih besar saat di-hover. Efek ini saya buat agar tampilan website terasa lebih dinamis dan tidak statis.

---
### 🔹 Section About Me

### > Kode Section About Me

Penjelasan :

* Pada bagian About ini, saya membagi konten menjadi tiga kolom yaitu Deskripsi Diri, Skills, dan Pengalaman. Layout dibuat menggunakan sistem grid Bootstrap agar tampil sejajar di layar besar dan otomatis menyesuaikan di layar kecil. Struktur ini dibuat supaya informasi tentang diri saya tersusun rapi dan mudah dibaca.

---

1️⃣ Struktur Section About

<img width="547" height="162" alt="Screenshot 2026-02-28 232252" src="https://github.com/user-attachments/assets/c0f47195-28ae-4664-ab57-9c4d06f73ee1" />


Penjelasan :

* Pada bagian ini saya membuat <section id="about" supaya bisa terhubung dengan menu navigasi di navbar. Class about-section digunakan untuk memberi styling khusus lewat CSS, seperti background dan jarak section. Di dalamnya saya pakai container agar isi tidak terlalu melebar ke pinggir layar. Lalu judul About Me saya buat dengan h2 dan class section-title text-center supaya tampil besar dan berada di tengah. Class row mt-5 dipakai untuk membuat satu baris layout dengan jarak atas agar tidak terlalu mepet dengan judul.

---

2️⃣ Kolom Deskripsi Diri

<img width="754" height="392" alt="Screenshot 2026-02-28 232309" src="https://github.com/user-attachments/assets/44b4c3cc-953b-44d4-a825-a1609b8012f1" />

Penjelasan :

* Bagian ini adalah kolom pertama dengan col-md-4 mb-4. Artinya, di layar medium ke atas akan mengambil 1/3 lebar layar, dan mb-4 memberi jarak bawah agar rapi saat turun ke bawah di layar kecil. Saya memakai about-card supaya tampilannya berbentuk card dan konsisten dengan kolom lainnya. Di dalamnya ada h4 sebagai judul dan p untuk isi deskripsi diri saya.

---

3️⃣ Kolom Skills (Dengan Vue)

<img width="693" height="392" alt="Screenshot 2026-02-28 232328" src="https://github.com/user-attachments/assets/fed2e798-1a1e-4f99-bc65-b7aaecbe83d6" />

Penjelasan:

* Ini kolom kedua, masih pakai col-md-4 mb-4 supaya sejajar dengan kolom lain. Bagian ini menampilkan daftar skill menggunakan v-for="skill in skills", artinya data diambil dari Vue dan ditampilkan secara otomatis berdasarkan isi array skills. Jadi kalau saya tambah data skill, tampilannya ikut bertambah tanpa ubah HTML. Progress bar dibuat dengan skill-bar dan skill-fill. Lebarnya diatur pakai :style="{ width: skill.percent + '%' }" supaya menyesuaikan nilai persen dari data. Angka persen juga ditampilkan di dalam <span>.

---

4️⃣ Kolom Pengalaman

<img width="907" height="415" alt="Screenshot 2026-02-28 232348" src="https://github.com/user-attachments/assets/035b0b44-c12c-48cd-8778-89f42eb1f244" />

Penjelasan:

* Ini kolom ketiga dengan struktur yang sama agar desainnya konsisten. Judul dibuat dengan h4 Pengalaman h4, lalu isi pengalaman ditampilkan dalam bentuk ul dan li supaya tersusun rapi seperti daftar. Saya memilih list karena lebih mudah dibaca dibanding paragraf panjang. Semua tetap dibungkus dengan about-card supaya tampilannya seragam dengan bagian Deskripsi dan Skills.

---

### Styling Section About (CSS)


1️⃣ CSS .about-section

<img width="672" height="785" alt="Screenshot 2026-02-28 233409" src="https://github.com/user-attachments/assets/398a5bdc-727b-4068-99a3-128c1dfe5a50" />

Penjelasan:

* Pada bagian ini saya mengatur tampilan utama section About. Background menggunakan kombinasi warna gradient agar terlihat lebih hidup. Saya juga menambahkan animasi gradientMove supaya background tidak statis, melainkan bergerak secara halus. Padding digunakan untuk memberi jarak atas dan bawah agar konten tidak terlalu rapat. Pseudo-element ::before saya gunakan sebagai elemen dekoratif berupa efek cahaya blur di sudut section, tanpa perlu menambah elemen HTML baru.

2️⃣ CSS Skills Bar


<img width="399" height="856" alt="Screenshot 2026-02-28 233438" src="https://github.com/user-attachments/assets/2ff492e0-b61b-4f34-86d3-ee85e76ab5bd" />

Penjelasan :

* Pada bagian ini saya mengatur tampilan progress bar pada kolom Skills. Class .skill-bar berfungsi sebagai wadah, sedangkan .skill-fill adalah bagian yang menunjukkan persentase kemampuan. Lebar .skill-fill mengikuti data dari Vue, sehingga bisa berubah sesuai nilai yang diberikan. Saya juga menambahkan animasi agar bar terlihat terisi secara bertahap saat muncul.

3️⃣ CSS About Card


<img width="343" height="838" alt="Screenshot 2026-02-28 233511" src="https://github.com/user-attachments/assets/bcf153a2-4859-4170-90c6-9f3434fc18da" />

Penjelasan:

* Class .about-card digunakan sebagai tempat untuk Deskripsi, Skills, dan Pengalaman. Saya memberikan efek transparan dan blur agar tampilannya lebih modern. Box-shadow dan border-radius membuat card terlihat lebih lembut.Efek hover ditambahkan agar card sedikit terangkat saat disentuh kursor, sehingga tampilan lebih keren.

---

### 🔹 Section Certificates

### > Kode Section Certificates

<img width="842" height="703" alt="Screenshot 2026-02-28 234512" src="https://github.com/user-attachments/assets/c744cd10-0c21-46e5-93cd-614c9138f4f2" />


Penjelasan :

* Pada bagian ini saya membuat section certificates untuk menampilkan daftar sertifikat yang pernah saya peroleh. Section ini dibuat terpisah agar lebih rapi dan mudah diakses melalui menu navigasi. Struktur layout menggunakan container dan sistem grid Bootstrap supaya tampilannya tetap teratur dan responsif. Setiap sertifikat ditampilkan menggunakan perulangan v-for dari Vue, sehingga data bisa ditambahkan langsung dari bagian JavaScript tanpa perlu menulis ulang kode HTML. Di dalam setiap item terdapat gambar sertifikat, tombol detail untuk melihat lebih detail isi dari sertifikat yang saya peroleh

