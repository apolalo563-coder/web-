Langkah 1: Persiapan Lingkungan (Environment Setup)

Sebelum mulai membuat kode, pastikan komputer Anda sudah terinstal Python dan pustaka (*library*) `pygame`.

1. **Instal Python:** Pastikan Python sudah terinstal di komputer Anda (bisa diunduh melalui python.org).
2. **Instal Pustaka Pygame:**
Buka Command Prompt (CMD) atau Terminal, lalu jalankan perintah berikut untuk menginstal pustaka game `pygame`:
```bash
pip install --upgrade pygame
Langkah 2: Membuat File Game

1. Buka teks editor atau IDE pilihan Anda (seperti VS Code, PyCharm, atau Notepad++).
2. Buat file baru dan beri nama **`game.py`**.
3. Salin kode program **Cyber Breaker** yang bersih di bawah ini ke dalam file `game.py`:

```python
import pygame
import random
import sys


 Langkah 3: Cara Menjalankan Game

1. Buka kembali terminal atau command prompt.
2. Masuk ke direktori/folder tempat Anda menyimpan file `game.py`.
3. Jalankan perintah:
```bash
python game.py

Langkah 4: Cara Memainkan Game

* **Memulai Permainan:** Pada tampilan menu utama berlatar belakang gelap bernuansa neon, tekan tombol **`ENTER`** pada keyboard untuk masuk ke arena permainan.
* **Menggerakkan Papan (Paddle):** Gunakan tombol **Panah Kiri / Panah Kanan** atau tombol **`A` / `D**` untuk menggeser papan pemantul ke kiri dan ke kanan agar bola tidak jatuh ke bawah.
* **Tujuan Permainan:** Pantulkan bola ke arah susunan balok (*bricks*) di bagian atas untuk menghancurkannya. Setiap balok yang hancur akan memberikan poin (balok di baris atas bernilai lebih tinggi).
* **Aturan Nyawa:** Anda memiliki total **3 Nyawa**. Jika bola jatuh melewati batas bawah layar, nyawa Anda akan berkurang 1. Permainan berakhir (*Game Over*) jika seluruh nyawa habis.
* **Kondisi Menang:** Anda akan menang jika berhasil menghancurkan seluruh balok yang ada di layar.
* **Menu Tambahan Setelah Selesai:** Baik dalam kondisi *Game Over* maupun *Win*, Anda bisa menekan tombol **`R`** untuk mengulang permainan dari awal atau tombol **`M`** untuk kembali ke menu utama.
