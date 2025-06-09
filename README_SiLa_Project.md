![SiLa Banner](https://user-images.githubusercontent.com/placeholder/sila-banner.png)

# ✋ SiLa - Sistem Interaktif Bahasa Isyarat

**SiLa** adalah aplikasi berbasis web yang dirancang untuk mengenali gesture Bahasa Isyarat Indonesia (SIBI) secara real-time menggunakan model machine learning yang dilatih dari koordinat landmark tangan MediaPipe. SiLa bertujuan untuk menjembatani komunikasi antara teman tuli dan masyarakat umum melalui teknologi yang mudah diakses.

🌐 **Coba sekarang:** [https://sila-app.vercel.app](https://sila-app.vercel.app)

---

## 📚 Tentang SiLa

SiLa merupakan proyek kolaboratif yang menggabungkan teknologi visi komputer, machine learning, dan antarmuka web modern. Aplikasi ini memungkinkan pengguna:

- Mengenali huruf A-Z dan gesture spesial seperti spasi menggunakan tangan.
- Melihat hasil klasifikasi gesture secara langsung dari kamera.
- Menyimpan hasil translate sebagai riwayat.
- Menggunakan antarmuka intuitif dengan mode belajar yang ramah pengguna.

---

## 👥 Tim Pengembang

| Nama                       | ID Mahasiswa     | Peran               | Institusi                              | Kontak |
|---------------------------|------------------|----------------------|----------------------------------------|--------|
| Davin Ghani Ananta Kusuma | MC299D5Y1599     | Machine Learning     | Universitas Pendidikan Indonesia       | [LinkedIn](http://www.linkedin.com/in/davin-kusuma22) |
| Nauval Gymnasti           | MC299D5Y1716     | Machine Learning     | Universitas Pendidikan Indonesia       | [LinkedIn](https://www.linkedin.com/in/nauval-gymnasti) |
| Rizka Alfadilla           | MC299D5Y1776     | Machine Learning     | Universitas Pendidikan Indonesia       | [LinkedIn](https://www.linkedin.com/in/rizka-alfadilla) |
| Elisa Oktaviana           | FC129D5X0057     | Frontend & Backend   | Politeknik Negeri Jember               | [LinkedIn](https://www.linkedin.com/in/elisa-oktaviana) |
| Dimas Rio Adisaputra      | FC156D5Y1043     | Frontend & Backend   | STT Terpadu Nurul Fikri                | [LinkedIn](http://www.linkedin.com/in/dimasrioadisaputra) |
| Zidan Dwi Permana         | FC299D5Y1778     | Frontend & Backend   | Universitas Pendidikan Indonesia       | [LinkedIn](https://www.linkedin.com/in/zidan-dwi-permana-7a8b4a24a/) |

---

## 🗂️ Repositori Utama

| Komponen               | Deskripsi                                                                                      |
|------------------------|-----------------------------------------------------------------------------------------------|
| `sila-ml-model`        | Model Machine Learning untuk klasifikasi gesture tangan menggunakan MLP dan 1D CNN.           |
| `sila-frontend`        | Aplikasi web interaktif dengan real-time gesture detection menggunakan TensorFlow.js.         |
| `sila-backend`         | REST API berbasis FastAPI untuk inference model dan penyimpanan riwayat gesture.              |

---

## 🚧 Roadmap Pengembangan

- [x] Deteksi gesture huruf A-Z + spasi
- [x] Real-time detection dari webcam
- [x] Penyimpanan riwayat translate
- [ ] Deteksi gesture untuk kata/kalimat
- [ ] Output suara dari teks hasil translate
- [ ] Dukungan Bahasa Isyarat lain (ASL, BISINDO)

---

> 💡 SiLa adalah langkah kecil menuju dunia yang lebih inklusif. Terima kasih telah mendukung kami!
