<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f8a44e04-1edd-4086-b019-5afcc0c58c9c" />

NAMA - Rangga Alfarizzy
NIM - 20240140059

# Praktikum 1 - Spring Boot Project

Proyek ini dikembangkan sebagai bagian dari tugas Praktikum 1 untuk membangun aplikasi web menggunakan framework **Spring Boot**. Fokus utama praktikum ini adalah konfigurasi dasar, pembuatan model data (Entity & DTO), serta implementasi arsitektur Service-Repository.

## 🚀 Fitur & Implementasi
- **Spring Initializr**: Setup proyek dengan Java 21/17 dan Maven.
- **RESTful API**: Menggunakan Spring Web.
- **Data Persistence**: Integrasi basis data MySQL menggunakan Spring Data JPA.
- **Object Mapping**: Implementasi **MapStruct** untuk konversi otomatis antara Entity dan DTO.
- **Validation**: Validasi input data menggunakan Hibernate Validator.
- **Boilerplate Reduction**: Menggunakan Project Lombok.

## 🛠️ Stack Teknologi
- **Bahasa**: Java
- **Framework**: Spring Boot 3.x
- **Build Tool**: Maven
- **Database**: MySQL
- **Library Utama**:
  - Spring Web
  - Spring Data JPA
  - MySQL Driver
  - Lombok
  - Validation
  - MapStruct (Konfigurasi Manual di `pom.xml`)

## 📂 Struktur Folder
Berdasarkan panduan praktikum, proyek ini mengikuti struktur berikut:
```text
src/main/java/com/deploy/praktikum
├── controller     # Controller untuk endpoint API
├── service        # Interface Logika Bisnis
│   └── impl       # Implementasi Logika Bisnis (UserServiceImpl)
├── repository     # Interface Akses Database (UserRepository)
├── model          # Data Model
│   ├── entity     # Representasi Tabel Database (User)
│   └── dto        # Data Transfer Object (UserDto, UserAddRequest)
├── mapper         # Interface MapStruct (UserMapper)
└── util           # Utility Class (ValidationUtil)
