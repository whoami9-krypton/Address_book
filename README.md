# 📱 Address Book – Project Overview

Address Book adalah aplikasi sederhana untuk mengelola daftar kontak.  
Project ini dibuat sebagai langkah awal sebelum implementasi, untuk mendefinisikan fitur, alur aplikasi, pseudocode, dan desain flowchart.

## 🎯 Tujuan Project
- Mendesain dasar aplikasi Address Book.
- Menentukan fitur yang dibutuhkan.
- Menjabarkan alur kerja aplikasi.
- Membuat pseudocode & flowchart untuk fitur utama.
- Menyiapkan struktur repository.

## ✨ Fitur Utama (Rencana)
1. Menampilkan daftar kontak
2. Menambah kontak baru
3. Mencari kontak
4. Mengedit kontak
5. Menghapus kontak

## 🧠 Alur Aplikasi
1. User membuka aplikasi.
2. Sistem menampilkan menu utama.
3. User memilih menu.
4. Sistem menjalankan fungsi.
5. Kembali ke menu utama.

## 📝 Pseudocode

### Menampilkan Kontak
```
FUNCTION showContacts(contactList):
    IF contactList is empty:
        PRINT "Tidak ada kontak"
    ELSE:
        FOR each contact IN contactList:
            PRINT contact.name, contact.phone, contact.email
```

### Menambah Kontak
```
FUNCTION addContact(contactList):
    INPUT name
    INPUT phone
    INPUT email
    CREATE newContact(name, phone, email)
    ADD newContact TO contactList
    PRINT "Kontak berhasil ditambahkan"
```

## 🔁 Flowchart
Tersedia pada folder `/flowcharts`.
