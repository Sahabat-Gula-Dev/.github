# Sahabat Gula 

<div align="center">
  <img src="https://img.shields.io/badge/PKM-2025-blue" alt="PKM 2025">
  <img src="https://img.shields.io/badge/Platform-Android-green" alt="Android">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</div>

## 📱 Tentang Aplikasi

**Sahabat Gula** adalah aplikasi seluler inovatif yang dirancang untuk membantu masyarakat Indonesia memantau asupan gula harian dan mengenali kandungan nutrisi makanan lokal menggunakan teknologi *computer vision*. Aplikasi ini bertujuan untuk mendukung mitigasi risiko diabetes melalui peningkatan literasi gizi dan kesadaran pola konsumsi sehat.

Proyek ini merupakan bagian dari **Program Kreativitas Mahasiswa (PKM) 2025**.

---

## 👥 Tim Pengembang

### Anggota Tim

| Nama | Program Studi | Role |
|------|---------------|------|
| **M. Ilham Abdul Shaleh** | Teknik Informatika | Backend Developer |
| **Rizki Rahman Maulana** | Teknik Informatika | Machine Learning Engineer |
| **Nazila Imkani** | Teknik Informatika | Mobile Developer |
| **Fitriana Hariyanti** | Pendidikan Dokter | Medical Advisor & Content |

### Dosen Pembimbing
**Dr. Eng. Budi Irmawati, S.Kom., M.T.**

---

## ✨ Fitur Utama

- 🔍 **Pengenalan Makanan Lokal**: Identifikasi makanan Indonesia melalui kamera menggunakan teknologi Machine Learning
- 📊 **Pemantauan Gula Harian**: Tracking asupan gula dan kalori secara real-time
- 🍽️ **Database Makanan Lokal**: Informasi nutrisi lengkap untuk makanan khas Indonesia
- 📈 **Analisis & Laporan**: Visualisasi data konsumsi harian, mingguan, dan bulanan
- 🎯 **Rekomendasi Personal**: Saran pola makan sehat berdasarkan profil pengguna
- 🔔 **Notifikasi Pengingat**: Reminder untuk mencatat makanan dan menjaga target konsumsi

---

## 🎯 Manfaat Aplikasi

| Manfaat | Deskripsi |
|---------|-----------|
| **Edukasi Gizi** | Meningkatkan kesadaran dan literasi gizi masyarakat, khususnya generasi muda, melalui informasi nutrisi yang mudah dipahami |
| **Mitigasi Diabetes** | Mendukung upaya pencegahan diabetes dengan monitoring konsumsi gula harian berbasis data visual dan analitik |
| **Teknologi Adaptif** | Implementasi computer vision yang disesuaikan dengan makanan lokal Indonesia untuk relevansi maksimal |

---

## 🛠️ Tech Stack

### 📱 Mobile Development (Android)
- **Bahasa**: Kotlin
- **Arsitektur**: MVVM (Model-View-ViewModel)
- **UI Framework**: Jetpack Compose / Android Views, Material Design 3
- **Networking**: Retrofit, OkHttp
- **Local Database**: Room
- **Image Processing**: CameraX, TensorFlow Lite
- **Dependency Injection**: Hilt/Dagger

### ⚙️ Backend
- **Runtime**: Node.js
- **Framework**: Hapi.js
- **Database**: Supabase (PostgreSQL)
- **Authentication**: JWT (JSON Web Tokens)
- **API Documentation**: Swagger/OpenAPI
- **Hosting**: Google Cloud Platform

### 🤖 Machine Learning
- **Framework**: TensorFlow, TensorFlow Lite
- **Model Architecture**: MobileNetV2 (Transfer Learning)
- **Dataset**: Custom dataset makanan Indonesia
- **Training Platform**: Google Colab / Google Cloud AI Platform
- **Optimization**: Quantization untuk mobile deployment

---


## 🚀 Instalasi & Penggunaan

### Prerequisites
- Android Studio Arctic Fox atau lebih baru
- JDK 11 atau lebih tinggi
- Android SDK (minimum API 24)
- Node.js v16+

### Clone Repository
```bash
git clone https://github.com/sahabat-gula/sahabat-gula-app.git
cd sahabat-gula-app
```

### Setup Mobile App
```bash
cd mobile
# Buka project di Android Studio
# Sync Gradle dan jalankan aplikasi
```

### Setup Backend
```bash
cd backend
npm install
cp .env.example .env
# Konfigurasi environment variables
npm run dev
```

---


---

## 📧 Kontak

Untuk pertanyaan atau saran, silakan hubungi:
- Email: info@sahabatgula.com
- Instagram: [@sahabatgula_kc](https://www.instagram.com/sahabatgula_kc/)

---

<div align="center">
  <p>Dibuat dengan ❤️ oleh Tim Sahabat Gula</p>
  <p>© 2025 Sahabat Gula. All rights reserved.</p>
</div>
