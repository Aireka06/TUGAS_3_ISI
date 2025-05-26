# Sistem Monitoring Suhu dan Kelembaban Fermentasi Kopi

Proyek ini bertujuan untuk mengembangkan sistem monitoring otomatis suhu dan kelembaban selama proses fermentasi biji kopi menggunakan sensor SHT20. Sistem ini dirancang untuk meningkatkan kualitas hasil fermentasi dengan pemantauan real-time, pencatatan data historis, dan visualisasi data melalui dashboard.

## 📌 Latar Belakang

Fermentasi merupakan tahapan penting dalam pasca panen kopi yang sangat menentukan profil rasa akhir dari biji kopi. Sayangnya, pengawasan suhu dan kelembaban selama fermentasi masih dilakukan secara manual oleh banyak petani, yang menyebabkan kualitas hasil fermentasi tidak konsisten.

Dengan bantuan teknologi, sistem monitoring otomatis dapat meminimalisir kesalahan, meningkatkan efisiensi, dan menjaga mutu kopi agar tetap tinggi.

## 🔧 Fitur Utama

- 🔍 **Pemantauan Real-time**: Monitoring suhu dan kelembaban secara langsung menggunakan sensor SHT20.
- 🧠 **Penyimpanan Data Historis**: Data dicatat secara berkala dan disimpan ke dalam database.
- 📊 **Visualisasi Dashboard**: Informasi suhu dan kelembaban ditampilkan melalui dashboard interaktif.
- ⚠️ **Notifikasi (Opsional)**: Sistem dapat dikembangkan lebih lanjut untuk memberikan peringatan jika parameter keluar dari batas ideal.

## 🛠️ Teknologi yang Digunakan

- **Sensor**: SHT20 (Suhu dan Kelembaban)
- **Mikrokontroler**: [STM32 / ESP32 / Arduino] *(disesuaikan dengan kebutuhan)*
- **Database**: InfluxDB / Firebase / MySQL *(opsional)*
- **Dashboard**: Grafana / Node-RED / Web App (HTML + JS)
- **Bahasa Pemrograman**: C/C++ untuk mikrokontroler, Python/JS untuk backend/frontend

## 🗂️ Struktur Direktori

