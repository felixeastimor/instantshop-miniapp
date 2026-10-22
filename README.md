# Tabel Quotation — Telegram Mini App (simulasi)

Halaman tabel Quotation untuk bot simulasi order Digital Instantshop (@InstantshopOrderFlowBot).

- Kolom mengikuti Order Form Instantshop: item, ukuran L x T (cm), qty, harga (per m² atau per unit), catatan/finishing, deadline; contact person + telepon.
- Isi awal (usulan dari chat WhatsApp/Wati) dikirim bot lewat bagian `#` tautan dan tidak pernah dikirim ke server ini.
- Hasil isian dikirim kembali ke bot lewat `Telegram.WebApp.sendData()`.
- `katalog.json` hanya berisi NAMA dan SATUAN barang dari master FoxPro — tanpa harga, tanpa HPP, tanpa data customer.
