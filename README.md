# Lirik Lagu

Proyek kecil berbasis Python untuk menampilkan lirik lagu dengan efek ketikan di terminal. Setiap file script menampilkan satu lagu dengan jeda waktu dan animasi teks yang dibuat menggunakan `threading` sehingga beberapa baris lirik bisa muncul secara bersamaan atau berurutan seperti tampilan karaoke sederhana.

## Daftar Lagu

- `multo.py` — lirik dengan tema yang lebih puitis dan melankolis
- `wide awake.py` — script dengan lirik dari lagu berjudul "Wide Awake"
- `love me not.py` — script dengan lirik dari lagu berjudul "Love Me Not"

## Fitur

- Animasi teks bertahap seperti mengetik satu per satu
- Penundaan waktu antar baris lirik
- Menggunakan modul bawaan Python tanpa dependency tambahan
- Dapat dijalankan langsung dari terminal

## Struktur Project

```text
Lagu/
├── README.md
├── multo.py
├── wide awake.py
├── love me not.py
└── .git
```

## Persyaratan

- Python 3.x
- Tidak membutuhkan library tambahan

## Cara Menjalankan

Buka terminal di folder project, lalu jalankan salah satu file berikut:

```bash
python ".\multo.py"
python ".\wide awake.py"
python ".\love me not.py"
```

Pada PowerShell, gunakan tanda kutip karena ada nama file yang mengandung spasi.

## Catatan

Setiap script memiliki daftar `lyrics` dan `delays` di dalamnya. Anda bisa mengubah isi lirik, kecepatan huruf (`speed`), maupun waktu jeda agar hasil tampilannya sesuai dengan keinginan.

## Lisensi

Proyek ini dibuat untuk kebutuhan belajar dan eksperimen Python. Jika ingin digunakan untuk tujuan lain, Anda dapat menyesuaikan sesuai kebutuhan.
