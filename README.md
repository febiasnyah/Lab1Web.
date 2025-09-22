# Pratikum 1
Kode HTML dasar:
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-22 212242" src="https://github.com/user-attachments/assets/a219c414-62f3-47d0-940e-407c623b4b8e" />

Membuat Paragraf:
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-22 140456" src="https://github.com/user-attachments/assets/7ad58896-0c3a-4000-97b9-d50fcbe90eb6" />

Menambahkan Judul:
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-22 140755" src="https://github.com/user-attachments/assets/8420bc28-9c93-4c24-8957-1d9606df6f63" />

Menformatkan Teks:
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-22 213331" src="https://github.com/user-attachments/assets/1dcbebae-50ad-4ce6-b0ca-001c106d2a13" />

Menyisipkan Gambar:
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-22 184620" src="https://github.com/user-attachments/assets/a4092e1c-d428-4684-a422-b40ee48eaff6" />

Menambahkan Hyperlink:
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-22 191728" src="https://github.com/user-attachments/assets/5ce2e628-9044-470f-bac5-a15aa32c4c94" />

# Jawablah Pertanyaan Berikut:
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah eror terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag < p > dengan tag < br >, berikan penjelasanya!
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasanya!
4. Untuk  mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proposional sebaiknya kedua atribut tersebut diisi semua atau tidak? berikan penjelasaannya!
5. Pada link tambahakan atribut target dengan nilai atribut bervariasi(_black,_self,_top,_parent), apa yang terjadi pada masing-masing nilai antribut tersebut?

# Jawab:
1. Jika kita mengubah kode HTML dengan atribut/tag yang benar makan browser tidak akan eror sedangkan jika kita mengubah kode HTML dengan atribut/tag yang salah maka HTML tidak akan memunculkan pop-up
2. Tag < p > (paragraph): Dipakai untuk membuat paragraf baru, Otomatis memberi jarak(margin) diatas dan dibawah teks. Sedangkan Tag < br > (Line Break): Dipakai untuk pindah baris (seperti menekan Enter sekali di keyboard), Tidak memberi jarak tambahan, hanya turun ke baris berikutnya. Jadi perbedaan utama dari keduanya adalah < p > Membuat Paragraf baru, < br > hanya memutus baris.
3. Atribut alt (Alternative Text): Berfungsi sebagai teks alternatif jika gambar gagal dimuat, juga dibaca oleh screen reader untuk membantu pengguna tunanetra, sangat penting untuk SEO ( Search Engine Optimization ). sedangkan Atribut Title: berfungsi untuk informasi tambahan (tooltip) saat pengguna mengarahkan kursor ke gambar, Tidak tampil jika gambar gagal dimuat (beda dengan ALT). Jadi, ALT lebih ke fungsi penting & aksesibilitas, sedangkan Title lebih ke kenyamanan pengguna.
4. jika kita hanya isi salah satu misalnya width saja Browser akan otomatis menyesuaikan ukuran sisi lain(height) agar proporsi (rasio) gambar tetap terjaga jadi gambar yang di hasilkan Tinggi gambar akan menyesuaikan agar tidak gepeng atau melebar. Jika kita isi keduanya misalnya Widht dan Height maka gamabr akan dipaksa sesuai ukuran yang ditentukan, Jika nilainya tidak sesuai dengan rasio asli gamabr maka gambar bisa terdistosi (terlalu gepeng atau melebar) gamabr bisa juga jadi gepeng kalau rasio aslinya tidak cocok. Agar tampilan gambar tetap proporsional, sebaiknya cukup isi salah satu atribut saja (Widht atau Height). Kalau ingin lebih fleksibel, biasanya diataur dengan CSS menggunakan properti max widht: 100%; height: auto; supaya gambar menyesuaikan ukuran layar (responsive design)
5. _black: buka tab/jendela baru, _self: buka di halaman sekarang (default), _top: buka di frame paling atas (keluar dari iframe), _parent: buka di frame induk.
