# 🌐 Portfolio Website  
## Grace Vies Angel – Sistem Informasi  

---

# 📌 Deskripsi Project

Website ini merupakan project portfolio pribadi yang saya buat sebagai bagian dari tugas mata kuliah Pemrograman Berbasis Web. Website ini berisi informasi mengenai diri saya, mulai dari perkenalan singkat, kemampuan yang saya miliki, pengalaman organisasi, hingga sertifikat yang pernah saya peroleh. Tujuan dari pembuatan website ini untuk menampilkan profil diri dalam bentuk website yang terstruktur dan responsif.

Dalam proses pembuatannya, saya menggunakan HTML sebagai struktur utama halaman, CSS untuk mengatur tampilan visual, Bootstrap 5 untuk membantu pengaturan layout agar responsif, serta Vue JS untuk menampilkan beberapa data seperti skills dan sertifikat secara lebih terstruktur.

---

# 🎨 Tampilan Setiap Section

## 🏠 Home (Hero Section)

Bagian Home merupakan tampilan pertama yang muncul ketika website dibuka. Pada bagian ini saya menampilkan nama lengkap, bidang yang saya tekuni yaitu *Creative Design & Management*, serta deskripsi singkat mengenai minat saya di bidang desain dan manajemen diri. Layout pada section ini dibagi menjadi dua kolom. Kolom sebelah kiri berisi teks perkenalan, sedangkan kolom sebelah kanan menampilkan foto profil. Saya menggunakan ukuran font yang cukup besar pada bagian nama agar langsung menjadi fokus utama saat halaman pertama kali dibuka.

<img width="1897" height="908" alt="image" src="https://github.com/user-attachments/assets/17952ac0-4d0b-4a64-bd5d-ca9e04e73bb5" />


---

## 👤 About Me

Pada bagian Section About Me berisi informasi yang lebih lengkap mengenai diri saya. Bagian ini dibagi menjadi tiga card utama dalam satu baris, yaitu Deskripsi Diri, Skills, dan Pengalaman. Pada bagian Deskripsi Diri, saya menjelaskan latar belakang saya sebagai mahasiswa Sistem Informasi serta minat saya dalam pengelolaan organisasi dan pengembangan kreativitas digital. Bagian Skills menampilkan daftar kemampuan dalam bentuk progress bar. Saya memilih menggunakan progress bar agar tingkat kemampuan dapat terlihat secara visual dan lebih mudah dipahami. Bagian Pengalaman berisi daftar kegiatan dan kontribusi yang pernah saya lakukan, khususnya dalam organisasi kampus. Informasi ditampilkan dalam bentuk poin agar lebih ringkas dan mudah dibaca.

<img width="1893" height="882" alt="image" src="https://github.com/user-attachments/assets/e60d64e7-f43a-4e6e-9014-94f375c7693c" />


---

## 🏆 Certificates

Section Certificates menampilkan daftar sertifikat yang pernah saya peroleh. Setiap sertifikat ditampilkan dalam bentuk card yang berisi gambar, tahun, dan judul kegiatan. Saya menambahkan tombol “Detail” pada setiap sertifikat. Ketika tombol tersebut diklik, akan muncul modal yang menampilkan gambar sertifikat dalam ukuran lebih besar. Jadi, pengunjung dapat melihat detail sertifikat tanpa harus berpindah halaman. Pada Section ini berfungsi sebagai bukti pencapaian dan pengalaman yang telah saya peroleh selama perkuliahan.

<img width="1899" height="862" alt="image" src="https://github.com/user-attachments/assets/a2208717-4ee3-47ab-81a5-c2183e09329a" />

<img width="1900" height="877" alt="image" src="https://github.com/user-attachments/assets/1330ebfc-6ff1-4d0f-8d10-e75568daffb2" />


---

# Penjelasan Code Setiap Section

## 🔹 Struktur Dasar HTML

Website ini diawali dengan struktur dasar HTML seperti berikut:
Bagian ini berfungsi sebagai kerangka utama halaman website. Meta viewport digunakan agar tampilan bisa menyesuaikan ukuran layar perangkat.

<img width="719" height="164" alt="image" src="https://github.com/user-attachments/assets/13f8150b-7d02-48ae-a172-ee3e0e9f4de0" />


## 🔹 Section Home

### > Kode Section Home (Hero Section)

<img width="801" height="579" alt="image" src="https://github.com/user-attachments/assets/1a872c08-45c8-4430-b456-79f31ca3e7f7" />

Pada bagian Home ini, saya membuat satu section utama dengan id home supaya bisa terhubung langsung dengan menu navigasi di atas. Jadi ketika tombol “Home” diklik, halaman akan langsung scroll ke bagian ini tanpa perlu pindah halaman.

Struktur layout-nya saya bagi menjadi dua kolom menggunakan sistem grid dari Bootstrap. Kolom pertama berisi teks seperti nama, role, dan deskripsi singkat tentang diri saya. Sedangkan kolom kedua digunakan untuk menampilkan foto profil. Dengan pembagian seperti ini, tampilan terlihat lebih seimbang antara teks dan gambar.

Saya juga menggunakan class container dan row agar isi konten tetap rapi dan menyesuaikan ukuran layar. Kalau dibuka di laptop tampil berdampingan, tapi kalau di HP otomatis menjadi satu kolom. Jadi tampilannya tetap nyaman dilihat di berbagai perangkat.

---

### > Kode Tampilan Foto (Hero Image Styling – CSS)

<img width="447" height="346" alt="image" src="https://github.com/user-attachments/assets/10f18a26-ea18-4fc9-9d30-d51ba3f23e9e" />

Pada bagian ini saya membuat wadah atau frame untuk foto profil menggunakan class .image-wrapper. Saya mengatur ukuran tetap 350px agar bentuknya konsisten dan tidak berubah-ubah. Warna background biru digunakan supaya selaras dengan tema website. Saya menggunakan display: flex agar posisi gambar berada di tengah secara horizontal dan berada di bagian bawah frame. Properti box-shadow saya tambahkan untuk memberi efek bayangan sehingga tampilannya tidak terlihat datar. Kemudian overflow: hidden digunakan supaya bagian gambar yang keluar dari frame tidak terlihat.

---

<img width="357" height="321" alt="image" src="https://github.com/user-attachments/assets/2e00c9d3-388b-4d3e-9002-67598db31ee4" />

Bagian ini saya gunakan untuk membuat efek cahaya di belakang foto. Elemen ::before adalah pseudo-element yang berfungsi sebagai dekorasi tambahan tanpa harus menambah elemen HTML baru. Saya menggunakan radial-gradient dengan warna putih transparan agar terlihat seperti pantulan cahaya. Efek blur ditambahkan supaya tampilannya lebih halus dan tidak terlalu tajam. Tujuannya agar foto terlihat lebih hidup dan tidak kaku.

---

<img width="383" height="349" alt="image" src="https://github.com/user-attachments/assets/ccdc3a36-cb99-4939-8c4e-9bd5a9dc3c8c" />

Pada bagian ::after, saya menambahkan efek gradasi di bagian bawah foto. Gradasi ini dibuat menggunakan linear-gradient agar bagian bawah gambar terlihat menyatu dengan background. Efek ini juga membantu memberikan kesan transisi yang lebih halus antara foto dan frame. Properti pointer-events: none digunakan agar elemen dekoratif ini tidak mengganggu interaksi pengguna.

---

<img width="430" height="178" alt="image" src="https://github.com/user-attachments/assets/dabd96f4-6bbf-4b9f-8760-2771e3977327" />

Pada bagian ini saya menambahkan efek ketika kursor diarahkan ke foto. Gambar akan sedikit terangkat dan membesar menggunakan transform, sehingga terlihat lebih interaktif. Selain itu, bayangan pada frame juga menjadi sedikit lebih besar saat di-hover. Efek ini saya buat agar tampilan website terasa lebih dinamis dan tidak statis.
