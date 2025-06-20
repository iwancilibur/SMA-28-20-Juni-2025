
# 📡 MQTT Interactive Robotics: ESP32, IoT & Android Kodular

Modul pembelajaran ini membahas tentang **pengembangan sistem IoT interaktif** berbasis **ESP32**, protokol komunikasi **MQTT**, dan antarmuka pengguna berbasis **Android menggunakan Kodular**. Dirancang untuk edukasi praktis dan eksploratif, modul ini sangat cocok untuk pelajar, pengajar, atau siapa pun yang tertarik dengan integrasi IoT dan Android apps.

---

## 👨‍🏫 Disusun Oleh

- **Iwan Muttaqin**  
  - Founder @ [inteknus.asia](https://inteknus.asia)  
  - Trainer @ Interactive Robotics  
  - Email: iwancilibur@gmail.com  
  - Social: [@iwancilibur](https://github.com/iwancilibur)

- **Gaza Haikal Adzandani**  
  - Email: gazahaikal.2086@gmail.com  
  - Social: [@childlimbo](https://github.com/childlimbo)

---

## 📘 Materi Utama

### 1. Pengenalan Microcontroller
- Arduino vs ESP32
- Instalasi dan penggunaan **Arduino IDE**
- Instalasi board ESP32

### 2. Blinking LED dan Serial Monitor
- Program dasar "Hello World" melalui **LED blink**
- Pemantauan data melalui **Serial Monitor**

### 3. Sensor DHT11
- Pembacaan data suhu & kelembaban
- Kondisi logika untuk suhu (misal: suhu > 31°C → “Mulai Panas”)

### 4. Aktuator: Relay
- Mengontrol perangkat AC 220V menggunakan relay
- Konsep aktuator listrik dan prinsip kerjanya

### 5. Dasar Jaringan
- Perbedaan jaringan kabel vs wireless
- Topologi jaringan dan perangkat (Modem, Access Point)

### 6. MQTT: Publish & Subscribe
- Penjelasan `Topic` dan `Payload`
- Contoh penggunaan:
  ```
  Topic   : iwan/sensorsuhu/kamar1  
  Payload : 25.5
  ```
- Penggunaan public broker: [HiveMQ Public Broker](https://www.hivemq.com/mqtt/public-mqtt-broker/)
- Instalasi library `MQTT.h` di Arduino IDE
- Tips: Gunakan client ID dan topic yang **unik**

### 7. Dashboard IoT Android dengan Kodular
- Membuat akun di [Kodular](https://www.kodular.io)
- Import Extension `UrsAI2MQTT.aix`
- Drag-and-drop komponen seperti Label, Button, dll.
- Blok logika kode dan uji coba dengan aplikasi Kodular Companion
- Customisasi UI Android

---

## 📂 Sumber Materi & Contoh Kode

🧾 **Materi lengkap & kode sumber dapat diakses di:**  
[https://github.com/iwancilibur/SMA-28-20-Juni-2025](https://github.com/iwancilibur/SMA-28-20-Juni-2025)

---

## 🧪 Evaluasi & Pengembangan

Modul ini ditutup dengan evaluasi serta e-book tambahan sebagai bahan pengayaan. Peserta dapat mengembangkan aplikasi dengan fitur lebih lanjut seperti:
- Pengendalian banyak sensor dan aktuator
- Penerapan notifikasi suhu ekstrem
- Integrasi AI sederhana untuk kontrol otomatis

---

## 📲 Tools yang Digunakan

| Tools        | Keterangan                               |
|--------------|------------------------------------------|
| Arduino IDE  | Pemrograman ESP32                        |
| Kodular      | Pembuatan aplikasi Android tanpa coding  |
| HiveMQ       | MQTT Broker Publik                       |
| DHT11        | Sensor Suhu & Kelembaban                 |
| Relay        | Aktuator untuk beban 220V                |

---

## 💬 Kontak & Komunitas

Silakan hubungi atau bergabung di komunitas untuk berdiskusi dan eksplorasi lebih lanjut:

- **Interactive Robotics**
- **AREI (Asosiasi Robotics Education Indonesia)**
- **Buitenzorg Makers Club**

---

## 🧠 Lisensi

Modul ini bersifat open source untuk edukasi. Diperbolehkan untuk digunakan dan dimodifikasi selama mencantumkan atribusi kepada pembuat.

---

## 🚀 Ayo Bangun Solusi IoT yang Cerdas dan Interaktif!
