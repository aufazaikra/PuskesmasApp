# 🏥 Sistem Antrian Digital Puskesmas - Spesifikasi Komponen OCL

Repository ini berisi **Spesifikasi Komponen Object Constraint Language (OCL)** untuk *Sistem Antrian Digital Puskesmas* yang dikembangkan sebagai bagian dari tugas akhir mata kuliah **Perangkat Lunak Berbasis Komponen (PLBK)**.

## 📌 Gambaran Umum

Tujuan dari proyek ini adalah untuk memodelkan komponen-komponen utama dari Sistem Antrian Digital Puskesmas menggunakan **spesifikasi OCL** yang tepat dan formal. Komponen-komponen ini merupakan bagian dari arsitektur sistem modular yang dirancang untuk mengelola sistem antrian pasien di puskesmas secara efisien, termasuk manajemen petugas, pengelolaan antrian, dan administrasi data pasien.

## 🧩 Komponen OCL

Proyek ini mencakup tiga spesifikasi interface OCL utama:

| ID Interface    | Deskripsi                                |
|-----------------|------------------------------------------|
| `IPetugasMgt`   | Menangani operasi yang berkaitan dengan manajemen petugas puskesmas, termasuk autentikasi, pengelolaan profil petugas, dan akses kontrol sistem antrian. |
| `IAntrianMgt`   | Mengelola operasi sistem antrian digital, termasuk pembuatan antrian baru, penentuan prioritas otomatis, pemrosesan antrian, dan monitoring status real-time. |
| `IPasienMgt`    | Mengelola operasi administrasi pasien, termasuk pendaftaran pasien baru, pembaruan data pasien, pencarian riwayat kunjungan, dan validasi data medis. |

Setiap interface berisi signature method, precondition, postcondition, dan invariant sesuai dengan standar OCL.

---

## 👨‍💻 Penulis

Proyek ini dikembangkan oleh:
- **Muhammad Aufa Zaikra** (NPM: 2208107010070)  
- **Teuku Farhansyah** (NPM: 2208107010090)

> Diserahkan sebagai tugas akhir untuk mata kuliah **Perangkat Lunak Berbasis Komponen**.
