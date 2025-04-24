# Sistem Pakar: Certainty Factor & Fuzzy Logic

Repositori ini berisi implementasi sistem pakar menggunakan dua pendekatan utama: **Certainty Factor (CF)** dan **Fuzzy Logic**. Dikembangkan menggunakan *Jupyter Notebook*, proyek ini bertujuan untuk memberikan pemahaman praktis tentang penerapan metode CF dan logika fuzzy dalam pengambilan keputusan berbasis pengetahuan.

## 📁 Struktur Proyek

- `CertaintyFactor.ipynb`  
 Notebook yang mendemonstrasikan penerapan metode Certainty Factor untuk inferensi dalam sistem pakar

- `FuzzyLogic.ipynb`  
 Notebook yang menampilkan implementasi logika fuzzy, termasuk definisi himpunan fuzzy, fungsi keanggotaan, dan proses inferensi fuzzy

## ⚙️ Prasyarat
Untuk menjalankan notebook ini, pastikan Anda memiliki:

- Python 3.x
- Jupyter Noteboo
- Pustaka Python berikut:
  - `numpy`
  - `pandas`
  - `matplotlib` (opsional, untuk visualisasi)
  
Anda dapat menginstal pustaka yang diperlukan menggunakan pip
```bash
pip install numpy pandas matplotlib
```

## 🚀 Cara Menjalankan

1 Klon repositori ini:

   ```bash
   git clone https://github.com/mrzack18/Sistem-Pakar-Certainty-Factor-Fuzzy-Logic-.git
   cd Sistem-Pakar-Certainty-Factor-Fuzzy-Logic-
   ```

2 Buka Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3 Pilih dan buka salah satu notebook (`CertaintyFactor.ipynb` atau `FuzzyLogic.ipynb`) untuk mempelajari implementasinya.

## 📖 Deskripsi Singkat

- **Certainty Factor (CF):**    Metode CF digunakan untuk menangani ketidakpastian dalam sistem pakar dengan memberikan nilai keyakinan terhadap suatu fakta atau aturan. Notebook ini menunjukkan bagaimana CF digunakan dalam proses inferensi untuk mencapai kesimpulan berdasarkan fakta yang terseda.

- **Fuzzy Logic:**    Logika fuzzy memungkinkan sistem untuk menangani data yang tidak pasti atau samar dengan menggunakan himpunan fuzzy dan fungsi keanggotaan. Notebook ini mendemonstrasikan bagaimana logika fuzzy diterapkan dalam pengambilan keputusan yang lebih fleksibel dibandingkan logika biner tradisional.
