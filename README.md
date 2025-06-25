# 🧩 Unscramble App - Game Edukatif dengan Jetpack Compose

**Aulia Putri Salsabila - 5025221281**

Dalam project ini, saya telah membangun aplikasi sederhana yaitu **Unscramble App**, sebuah game edukatif Android berbasis **Jetpack Compose**. Aplikasi ini menantang pengguna untuk menebak kata-kata acak (*unscrambled words*) dengan antarmuka modern dan interaktif.

---

## ✨ Fitur Utama

- Menampilkan kata acak yang harus ditebak  
- Sistem skor untuk jawaban yang benar  
- Navigasi sederhana berbasis Compose  
- Arsitektur MVVM menggunakan ViewModel dan State  

---

## 🗂️ Struktur File Penting

### `com.example.unscramble`

- `MainActivity.kt`  
  → Titik masuk aplikasi. Mengatur UI menggunakan `GameScreen`.

- `data/WordsData.kt`  
  → Berisi daftar kata-kata acak yang digunakan dalam permainan.

- `ui/GameScreen.kt`, `GameViewModel.kt`, `GameUiState.kt`  
  → Komponen UI dan logika game menggunakan ViewModel serta state Compose.

---

### `com.example.unscramble (test)`

- `ui.test/GameViewModelTest.kt`  
  → Unit test untuk `GameViewModel`.

- `data/WordsData.kt`  
  → Versi test dari `WordsData.kt` untuk keperluan pengujian.

---

## 🧠 Kesimpulan

Aplikasi ini menggunakan struktur arsitektur yang rapi dan terpisah:

- **Data (model):** `WordsData.kt`  
- **Logika (ViewModel):** `GameViewModel.kt`  
- **UI (View):** `GameScreen.kt`, dikendalikan dari `MainActivity.kt`  
- **Pengujian:** `GameViewModelTest.kt`  

---

## 📷 Preview
<p align="center">
  <img src="https://github.com/user-attachments/assets/4a1b5608-ee5d-4caf-a79a-cfd3185d3e45" alt="screenshot1" width="45%" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/ea831c4c-b56d-4ee1-95a6-3f1410e58f89" alt="screenshot2" width="45%" />
</p>

---

## 🔗 Referensi

- [Android Codelab - ViewModel and State in Compose](https://developer.android.com/codelabs/basic-android-kotlin-compose-viewmodel-and-state?hl=id)

