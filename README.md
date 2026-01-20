[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/0f7NjB2l)

# LAPORAN PROJECT: JS LEARNING PLATFORM

**JS LEARNING PLATFORM** aadalah sebuah Learning Management System (LMS) yang dirancang khusus untuk memfasilitasi pembelajaran JavaScript secara terstruktur, dari tingkat dasar hingga mahir. Platform ini menyediakan 27 lesson lengkap dengan fitur progress tracking yang memudahkan learner untuk memantau perkembangan belajar mereka.

**Tujuan Project**

Menyediakan platform pembelajaran JavaScript yang terstruktur dan mudah diakses
Implementasi sistem authentication untuk mengelola user
Membangun REST API sebagai backend service
Mengimplementasikan progress tracking untuk monitoring pembelajaran
Menciptakan user experience yang intuitif dan responsif

**Apa itu API?**

API (Application Programming Interface) adalah sekumpulan protokol dan tools yang memungkinkan dua aplikasi atau sistem untuk berkomunikasi satu sama lain.
Dalam Project Ini:
API berfungsi sebagai jembatan komunikasi antara Frontend (tampilan website) dan Backend (server yang memproses data).

Cara Kerja:



```
Frontend (User Interface)
    ↓
  Request ke API
    ↓
Backend (Server/Database)
    ↓
  Response dari API
    ↓
Frontend (Tampilkan Data)
```

**Contoh API Endpoint dalam Project:**

POST /api/auth.php?action=register - Mendaftarkan user baru
POST /api/auth.php?action=login - Login user
GET /api/courses.php - Mengambil daftar course
GET /api/courses.php?id=course_001 - Mengambil detail course beserta modules dan lessons
POST /api/progress.php - Menyimpan progress pembelajaran user
GET /api/progress.php?userId=X&courseId=Y - Mengambil progress user




---

## 🚀 Fitur Unggulan

1. User Authentication

Register dan Login dengan validasi
Password encryption menggunakan bcrypt
Session management dengan localStorage

2. Dashboard Interaktif

Tampilan overview statistics (total courses, completed lessons, progress percentage)
Welcome card dengan informasi user
Quick access ke course

3. Course Management

1 Course lengkap: "Modul JavaScript Lengkap"
27 Lessons terbagi dalam 6 Modules
Konten pembelajaran dari PDF yang diparsing manual

4. Progress Tracking

Real-time progress update
Mark lesson as complete
Progress bar visualization
Data tersimpan permanen di backend

5. Interactive Learning

Lesson reader dengan konten HTML formatted
Navigation (Previous/Next lesson)
Sidebar lesson list dengan indicator completed
Responsive design (mobile-friendly)

6. Modern UI/UX

Dark mode support
Clean & modern interface menggunakan Mazer template
Smooth animations dan transitions

7. Bonus: Quiz System

5 soal pilihan ganda
Auto-grading system
Score calculation

---

## 💻 Teknologi yang Digunakan

<h2>Backend: </h2>

PHP Native (tanpa framework)
REST API Architecture
JSON Files sebagai Database
bcrypt untuk password hashing
CORS enabled untuk cross-origin requests

<h2>Frontend:</h2>

HTML5, CSS3, JavaScript (Vanilla)
Bootstrap 5 (Mazer Dashboard Template)
Fetch API untuk HTTP requests
LocalStorage untuk session management

<h2>Database:</h2>

JSON Files (users.json, courses.json, modules.json, lessons.json, progress.json, quizzes.json)

<h2>Deployment:</h2>

InfinityFree Hosting (free web hosting dengan PHP support)
GitHub untuk version control dan source code repository

<h2>Development Tools:</h2>
XAMPP (Apache + PHP local development)
Visual Studio Code (code editor)
Git & GitHub (version control)
Chrome DevTools (debugging)

---

## ⚙️ Instalasi & Setup

Ikuti langkah berikut untuk menjalankan proyek ini di komputer lokal Anda:

### 1. Clone Repository
```
Prerequisites:

  XAMPP (Apache + PHP 7.4 atau lebih tinggi)
  Git
  Web Browser (Chrome/Firefox/Edge)


git clone https://github.com/JTIK-PNL/2025-trkj-2c-projectapi-engineer.git
```

---

### **Langkah 2: Pindahkan ke Folder XAMPP**

1. Copy folder project yang sudah di-clone
2. Paste ke: `C:\xampp\htdocs\`
3. Rename folder jadi: `js-learning-platform`

Struktur akhir:
```
C:\xampp\htdocs\js-learning-platform\
```

---

### **Langkah 3: Start Apache Server**

1. Buka **XAMPP Control Panel**
2. Klik **"Start"** pada **Apache**
3. Tunggu hingga status Apache menjadi **hijau/running**

---

### **Langkah 4: Akses Website**

Buka browser dan ketik:
```
http://localhost/js-learning-platform/frontend/login.html
```

---

### **Langkah 5: Register & Login**

1. Klik **"Daftar di sini"** untuk register
2. Isi:
   - Nama Lengkap
   - Email
   - Password (minimal 6 karakter)
3. Klik **"Sign Up"**
4. Setelah berhasil, akan redirect ke halaman login
5. Login dengan email dan password yang baru dibuat

---

### **Langkah 6: Mulai Belajar**

1. Setelah login, masuk ke **Dashboard**
2. Klik **"My Courses"** di sidebar
3. Expand module yang ingin dipelajari
4. Klik lesson untuk mulai membaca
5. Setelah selesai, klik **"Mark as Complete"**
6. Progress otomatis tersimpan

---

## **🔗 LINK PROJECT**

### **Live Demo:**
```
https://jslms.great-site.net/frontend/login.html
```

### **GitHub Repository:**
```
https://github.com/JTIK-PNL/2025-trkj-2c-projectapi-engineer