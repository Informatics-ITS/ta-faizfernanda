# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Muhamad Faiz Fernanda  
**NRP**: 5025211186
**Judul TA**: Pendekatan Berbasis Jaringan Saraf dan Graf untuk Memahami Daya Tarik Visual Foto Makanan
**Dosen Pembimbing**: Shintami Chusnul Hidayati, S.Kom., M.Sc., Ph.D. 


---

## 📺 Demo Aplikasi  
Embed video demo di bawah ini :  

[![Demo Aplikasi](https://i.ytimg.com/vi/zIfRMTxRaIs/maxresdefault.jpg)](https://www.youtube.com/watch?v=iov6YSh2Rks)  
*Klik gambar di atas untuk menonton demo*

---

*Konten selanjutnya hanya merupakan contoh awalan yang baik. Anda dapat berimprovisasi bila diperlukan.*

## 🛠 Panduan Instalasi & Menjalankan Software  

### Prasyarat  
| Library                   | Keterangan                                                                         |
| ------------------------- | ---------------------------------------------------------------------------------- |
| `streamlit`               | Membangun antarmuka aplikasi klasifikasi estetika berbasis web                     |
| `pandas`                  | Manipulasi dan analisis data tabular (CSV, DataFrame)                              |
| `numpy`                   | Operasi numerik, array, dan vektor fitur gambar                                    |
| `torch`                   | Framework utama untuk training model GCN/GAT                                       |
| `torch_geometric`         | Ekstensi PyTorch untuk model berbasis graf seperti GCN dan GAT                     |
| `tensorflow`              | Ekstraksi fitur citra menggunakan model CNN InceptionResNetV2                      |
| `sklearn`                 | Normalisasi data fitur dan evaluasi model (StandardScaler, classification\_report) |
| `networkx`                | Membangun struktur graf dari patch gambar                                          |
| `joblib`                  | Menyimpan model PCA atau objek Python lainnya dalam format efisien                 |
| `matplotlib`              | Visualisasi metrik performa model seperti confusion matrix                         |
| `PIL`                     | Membaca dan memproses gambar input                                                 |
| `json`                    | Memuat file fitur gambar dalam format JSON                                         |
| `re`                      | Melakukan preprocessing teks dengan ekspresi reguler (jika diperlukan)             |
| `os`                      | Navigasi file dan folder dataset                                                   |
| `glob`                    | Membaca banyak file gambar dalam satu folder                                       |
| `streamlit.components.v1` | Menyisipkan HTML kustom untuk visualisasi graf dan prediksi                        |
| `IPython.display`         | Menampilkan HTML atau elemen interaktif di notebook (opsional)                     |


### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/TA.git
   ```
2. **Instalasi Dependensi**
   ```bash
   cd [folder-proyek]
   pip install -r requirements.txt  # Contoh untuk Python
   npm install  # Contoh untuk Node.js
   ```
3. **Konfigurasi**
- Salin/rename file .env.example menjadi .env
- Isi variabel lingkungan sesuai kebutuhan (database, API key, dll.)
4. **Jalankan Aplikasi**
   ```bash
   python main.py  # Contoh untuk Python
   npm start      # Contoh untuk Node.js
   ```
5. Buka browser dan kunjungi: `http://localhost:3000` (sesuaikan dengan port proyek Anda)

---

## 📚 Dokumentasi Tambahan

- [![Dataset Image]](https://drive.google.com/drive/folders/1CttrL0ZTSvhi050xBYORP_fMN2ddDKvh?usp=sharing)
- [![Dataset All_Fitur_CSV]](https://drive.google.com/file/d/1fQ0JrFQrvTZOxW6nArVJDE8U_qsDIhrX/view?usp=sharing)
- [![Dataset_All_Fitur_PT]](https://drive.google.com/file/d/1zZyOquMbmsu2xMeiFSXodm9yxcyWYHUc/view?usp=sharing)

---

## ✅ Validasi

Pastikan proyek memenuhi kriteria berikut sebelum submit:
- Source code dapat di-build/run tanpa error
- Video demo jelas menampilkan fitur utama
- README lengkap dan terupdate
- Tidak ada data sensitif (password, API key) yang ter-expose

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: [faizfernan24@gmail.com]
- Pembimbing Utama: [shintami@if.its.ac.id]
