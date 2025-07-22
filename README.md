<p align="center">
  <img src="https://files.catbox.moe/oso7xd.jpg" width="100%" alt="Yousoo CON Banner">
</p>

# 🛡️ YosoNumber.json – Sistem Keamanan Bot WhatsApp Will Graham

**YosoNumber.json** adalah file database berformat **JSON** yang digunakan sebagai sistem keamanan internal untuk bot WhatsApp **Will Graham** (buatan Yousoo). File ini menyimpan data validasi berupa **nomor bot** dan **IP server** agar hanya perangkat yang sah yang dapat menjalankan bot ini.

---

## 🔐 Fungsi Keamanan

Bot hanya akan berjalan jika:

- Nomor WhatsApp yang digunakan sesuai dengan yang tercatat di `YosoNumber.json`.
- IP server saat ini sesuai dengan IP yang tersimpan.

Jika tidak sesuai, bot akan **otomatis dihentikan** untuk mencegah penyalahgunaan.

---

## 🧾 Format YosoNumber.json

```json
{
  "nomor": [
    "6281234567890"
  ],
  "ip": [
    "123.45.678.90"
  ]
}
