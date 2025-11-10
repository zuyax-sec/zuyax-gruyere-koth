# ℤ𝕦𝕪𝕒𝕏 𝔾𝕣𝕦𝕪𝕖𝕣𝕖 ℂ𝕋𝔽

> **Mode:** King of The Hill (KOTH)  
> **Host:** [https://google-gruyere.appspot.com/XXXXXXXXXXXX/](https://google-gruyere.appspot.com/XXXXXXXXXXXX/) ← *gunakan satu link arena yang ditetapkan admin*  
> **Style:** Exploit, Deface, Survive  

---

## 《⌖》 Objective

Seluruh peserta bermain di **satu arena bersama** (satu instance Gruyere).  
Tujuannya adalah menjadi **King**, yaitu pemain yang **berhasil menguasai arena** dengan cara mengeksploitasi celah web dan memodifikasi tampilan utama (deface) untuk menampilkan identitasnya.

---

## 《모》 Cara Main

1. Gunakan **satu link arena resmi** yang dibagikan oleh admin:
   Contoh : https://google-gruyere.appspot.com/XXXXXXXXXXXX/

(Admin akan mengumumkan ID-nya di awal event)

2. Semua pemain **bermain di arena yang sama** — rebutan menjadi King.

3. Eksploitasi boleh berupa:
- XSS, CSRF, cookie hijacking, upload bug, code injection, dll.
- Modifikasi tampilan web dengan tanda unik kamu (“King: [nama kamu]”).

4. Setiap kali kamu berhasil mengambil alih (menjadi King):
- Pastikan website tetap hidup dan dapat diakses.
- Jangan menghapus seluruh konten (tujuan: kontrol, bukan penghancuran).

---

## 《🜲》 Aturan King of The Hill

| Kondisi | Keterangan |
|----------|------------|
| **King aktif** | Pemain yang identitasnya terakhir kali muncul di halaman utama arena. |
| **Arena bersama** | Semua peserta bermain di 1 link Gruyere yang sama. |
| **Boleh menyerang** | Arena publik event saja (bukan instance pribadi atau server lain). |
| **Menang permanen** | Jika kamu tetap menjadi King selama 15 menit tanpa digulingkan. |
| **Etika wajib** | Tidak menghapus total data, tidak brute-force, tidak DDoS, tidak memblokir akses pemain lain. |

---

## 《✔》 Cara Klaim King

1. Ambil **screenshot bukti**:
- Tampilkan halaman utama arena (dengan URL + identitas kamu sebagai King).  
- Sertakan **timestamp (jam di layar)**.

2. Kirim klaim kemenangan melalui formulir berikut:  
📜 **[Formulir Claim King (Google Form)](https://forms.gle/XXXXXXX)**  
*(link akan disediakan oleh admin)*

3. Admin akan memverifikasi klaim dan meng-update scoreboard.

---

## 《🗐》 Skor Manual (untuk admin)

| Jenis Kemenangan | Poin |
|------------------|------|
| Berhasil Deface & Bertahan 1 minggu | 10 |
| Deface Sementara (kurang dari 7 hari) | 5 |
| Laporan Celah Baru (tanpa deface) | +3 Bonus |
| Merusak total / crash arena | 0 (tidak valid) |

---

## 《⏣》 Tips Eksploitasi

- Lihat kode sumber (`Source code` link di halaman utama Gruyere).  
- Cari XSS, CSRF, upload vuln, atau manipulasi cookie.  
- Pelajari payload aman yang tidak menghancurkan instance.

---

> _“Hack to learn, not to harm.”_


