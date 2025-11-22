# 📰 Event Kampus Locator (Build 2 – Final)

**Nama:** Inez Dea Ariska  
**NIM:** STI202303642  
**Proyek:** Event Kampus Locator 2  
**Modul W11–12:** Flutter – Servis Lokasi, Peta (Google Maps & OSM)

---

## 1. 🎨 UI Dark Mode & Info Terpusat

Antarmuka kini menggunakan **Dark Mode** dengan tampilan yang lebih modern.  
Informasi lokasi seperti **Latitude, Longitude, Speed, dan Heading**, ditampilkan dalam **kartu informasi (Info Card)** lengkap dengan status waktu pengambilan data.

<p align="center">
  <img src="assets/images/build2_ui.jpg" width="300"><br>
  <em>Gambar 1. Tampilan Utama Dark Mode & Info Card</em>
</p>

---

## 2. 🔋 Kontrol Akurasi & Background Service

Build 2 menambahkan fitur pengaturan akurasi untuk mengoptimalkan penggunaan baterai.  
Pengguna dapat memilih:

- **High Accuracy (GPS Mode):** Mendukung tracking dengan notifikasi Background Service.
- **Low Accuracy (WiFi/Cell Tower Mode):** Lebih hemat daya.

Semua dikendalikan melalui **Toggle Switch** di pojok kanan atas.

<p align="center">
  <img src="assets/images/build2_battery.jpg" width="300"><br>
  <em>Gambar 2. Toggle Akurasi & Peringatan Baterai</em>
</p>

---

<p align="center">
  <img src="assets/images/build2_background.jpg" width="300"><br>
  <em>Gambar 3. Notifikasi Background</em>
</p>

---

## 3. 📍 Smart Sorting & Peta Marker

Daftar event kini:

- Ditampilkan dengan ikon visual.
- **Diurutkan otomatis** dari event terdekat ke terjauh.
- Mendukung tampilan peta menggunakan **Google Maps** atau **OpenStreetMap (OSM)**.

Marker yang digunakan:

- **Marker Merah:** Lokasi pengguna
- **Marker Biru:** Lokasi event

<p align="center">
  <img src="assets/images/build2_list.jpg" width="300"><br>
  <em>Gambar 4. Smart List Event</em>
</p>

---

<p align="center">
  <img src="assets/images/build2_marker_gmaps1.jpg" width="300"><br>
  <em>Gambar 5. Marker Peta (Google Maps)</em>
</p>

---

<p align="center">
  <img src="assets/images/build2_marker_gmaps2.jpg" width="300"><br>
  <em>Gambar 6. Marker Peta (Google Maps)</em>
</p>

---

<p align="center">
  <img src="assets/images/build2_marker_osm.jpg" width="300"><br>
  <em>Gambar 7. Marker Peta (OSM)</em>
</p>

---

<p align="center">
  <img src="assets/images/build2_marker_osmklik.jpg" width="300"><br>
  <em>Gambar 8. Marker Peta (OSM) (Jika di klik)</em>
</p>

---

## 🚀 Perubahan Utama di Build 2

✔️ UI Dark Mode  
✔️ Info Card dengan Timestamp  
✔️ Toggle Akurasi (High/Low)  
✔️ Background Service Notification  
✔️ Smart Sorting Event  
✔️ Marker Peta dengan Warna Beda

---
