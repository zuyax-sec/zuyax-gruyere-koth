# 🧰 Admin Manual — Above the Hill (Google Gruyere Arena)

---

## 🗁 Struktur Event

| Komponen | Fungsi |
|-----------|--------|
| **Google Gruyere (1 arena)** | Tempat semua peserta bermain dan berebut King. |
| **Google Form** | Media peserta klaim kemenangan. |
| **Scoreboard (XLSX/CSV)** | Rekap manual oleh admin. |
| **Grup Komunikasi (Discord/WhatsApp)** | Tempat share status King & koordinasi. |

---

## 🌣 Setup Awal

1. Buat **1 instance Gruyere resmi**:  
   - Buka: [https://google-gruyere.appspot.com/start](https://google-gruyere.appspot.com/start)  
   - Catat ID unik-nya, misalnya `123456789012`.  
   - Gunakan URL arena:  
     ```
     https://google-gruyere.appspot.com/123456789012/
     ```
   - Ini adalah **arena tunggal event**.

2. Pastikan semua peserta tahu bahwa mereka bermain di **link yang sama**.

3. Upload file `CTF-Rules-Google-Gruyere.md` dan `CTF-Admin-Manual.md` ke repo GitHub event.

---

## 🖥 Setup Google Form

**Judul:**  
`Claim King — Above the Hill (Google Gruyere Arena)`

**Deskripsi:**  
> Gunakan form ini untuk mengklaim posisi King setelah kamu berhasil mengubah tampilan arena.

**Pertanyaan yang disarankan:**
1. Nama lengkap / nickname  
2. Bukti screenshot (upload file atau link)  
3. Waktu berhasil menjadi King (format HH:MM)  
4. Deskripsi singkat exploit / langkah yang digunakan  
5. Catatan tambahan (opsional)

Setelah selesai:
- Aktifkan pengumpulan file (bila butuh upload gambar).
- Hubungkan ke Google Sheets untuk pencatatan otomatis.
- Copy link form dan masukkan ke rules file di bagian *Claim Kemenangan*.

---

## 🛢 Scoreboard Template

Gunakan file berikut (tersedia di repo event):

- [Download CSV/XLSX Template](./ctf_scoreboard_template.xlsx)

| Kolom | Keterangan |
|--------|-------------|
| Nama | Pemain |
| Screenshot Link | Bukti visual |
| Waktu Klaim | HH:MM |
| Valid | Yes/No |
| Poin | 5 / 10 / +Bonus |
| Catatan | Tambahan admin |

---

## ☕︎ Jalannya Permainan

1. Admin share link arena Gruyere ke semua peserta.  
2. Semua pemain berkompetisi di arena yang sama.  
3. Setiap kali ada King baru, pemain mengisi form klaim.  
4. Admin verifikasi bukti, lalu update scoreboard.  
5. Setelah periode tertentu (misal 15 menit stabil), pemain resmi menjadi **King of The Hill**.

---

## ⚠☣-Catatan Penting-☢⚠

- Jangan ubah konfigurasi arena saat permainan berlangsung.  
- Jika arena rusak total (error 500 / crash):  
  - Admin buat ulang instance baru.  
  - Update link baru di repo & grup.  
- Batasi jumlah peserta aktif agar arena tidak overload.

---

## ⁴⁰⁴ Penutup

> _“Di atas bukit hanya ada satu King, tapi banyak yang belajar mendaki.”_

---
