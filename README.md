# Tugas 3 - Aplikasi Lemonade

Aplikasi Lemonade interaktif berbasis **Jetpack Compose** dan **Kotlin**.  
Pengguna mengetuk layar melalui 4 tahapan: memetik lemon, memerasnya (2-4 ketukan acak), meminum lemonade, dan memulai ulang.

## Alur Aplikasi (State Machine)

| State | Gambar | Aksi |
|:-----:|:------:|:----:|
| 1. Pohon Lemon | `lemon_tree` | Ketuk untuk memetik lemon |
| 2. Peras Lemon | `lemon_squeeze` | Ketuk 2-4 kali (acak) untuk memeras |
| 3. Minum Lemonade | `lemon_drink` | Ketuk untuk meminum |
| 4. Gelas Kosong | `lemon_restart` | Ketuk untuk mulai lagi |

## Yang Dipelajari

- Button Click Handlers di Jetpack Compose
- Perubahan gambar dinamis dengan `when` + state
- Logika angka acak (`(2..4).random()`)
- Manajemen state dengan `remember` + `mutableStateOf`

## Referensi

Google Developer Codelab: [Practice: Adding Buttons to an App](https://developer.android.com/codelabs/basic-android-kotlin-compose-button-click-practice-problem)

## Identitas

- **Nama:** Fatih Jawwad Al Mumtaz
- **NIM:** 452024611047
- **Kelas:** A2
- **Mata Kuliah:** Pemrograman Mobile
- **Dosen:** Wahid Alfaridsi Achmad Zein, M.Kom.
- **Universitas:** Universitas Darussalam Gontor
