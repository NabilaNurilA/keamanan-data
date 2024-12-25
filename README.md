# Tugas Kriptografi dan Steganografi

## Nama Tugas
Aplikasi Implementasi Kriptografi dan Steganografi

## Isi Tugas
Proyek ini berisi implementasi algoritma kriptografi dan steganografi sederhana dalam Python. Proyek mencakup berbagai algoritma dan pendekatan untuk mengamankan data, seperti DES, Enigma, Caesar Cipher, dan Steganografi.

## Deskripsi File
1. **steganogui.py**  
   File ini adalah implementasi steganografi menggunakan modul `stegano`. Pengguna dapat menyembunyikan pesan rahasia dalam gambar atau mengungkap pesan yang tersembunyi.  
   - *Fitur*: Menyembunyikan dan menampilkan pesan rahasia dalam file gambar.  
   - *Cara Menjalankan*: Jalankan file di terminal Python menggunakan perintah `python steganogui.py`.

2. **des.py**  
   File ini mengimplementasikan algoritma DES (Data Encryption Standard) menggunakan antarmuka GUI berbasis `Tkinter`.  
   - *Fitur*: Mengenkripsi dan mendekripsi teks menggunakan kunci 8 karakter.  
   - *Cara Menjalankan*: Jalankan file menggunakan Python, misalnya `python des.py`.

3. **enigma.py**  
   File ini adalah simulasi mesin Enigma berbasis GUI untuk mengenkripsi dan mendekripsi pesan.  
   - *Fitur*: Memproses teks menggunakan mekanisme rotor yang menyerupai mesin Enigma historis.  
   - *Cara Menjalankan*: Gunakan perintah `python enigma.py` untuk membuka antarmuka GUI.

4. **chipergui.py**  
   Implementasi Caesar Cipher sederhana dalam mode terminal. Pengguna dapat mengenkripsi dan mendekripsi pesan dengan menentukan nilai pergeseran.  
   - *Fitur*: Mengenkripsi dan mendekripsi pesan teks.  
   - *Cara Menjalankan*: Jalankan file dengan perintah `python chipergui.py`, lalu ikuti instruksi di terminal.

## Cara Menjalankan
1. Pastikan Python 3 telah terinstal di sistem Anda.
2. Install pustaka yang diperlukan menggunakan:
   ```bash
   pip install stegano pycryptodome
