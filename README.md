# Kriptografi_Pertemuan-3

- Nama             : Nurul Fajri
- Nim              : 312110506
- Kelas            : TI.21.C.1
- Dosen Pengampu   : Ahmad Turmudi Zy, S.Kom., M.Kom
- Mata Kuliah      : Kriptografi


#
-berikut penjelasan singkat tentang sistem login dengan enkripsi Vigenère Cipher yang telah saya implementasikan:

-Fungsi generate_vigenere_table()
-Fungsi ini digunakan untuk membuat tabel Vigenère Cipher, yang merupakan tabel pergeseran alfabet berdasarkan kunci.

-Fungsi encrypt_vigenere(plaintext, key)
-Fungsi ini mengenkripsi teks (plaintext) menggunakan kunci (key) dengan metode Vigenère Cipher. Enkripsi dilakukan dengan memanfaatkan tabel Vigenère Cipher yang telah dibuat sebelumnya.

-Fungsi decrypt_vigenere(ciphertext, key)
-Fungsi ini melakukan dekripsi teks terenkripsi (ciphertext) menggunakan kunci (key) dengan metode Vigenère Cipher. Dekripsi juga menggunakan tabel Vigenère Cipher yang telah dibuat.

-Main Program

-Pada contoh penggunaan, sebuah username dan password diinisialisasi.
-Password dienkripsi menggunakan Vigenère Cipher dengan username sebagai kunci.
-Setelah itu, password terenkripsi dapat disimpan di database atau tempat penyimpanan yang aman.
-Pada proses login:
-Pengguna diminta memasukkan username dan password.
-Password yang dimasukkan oleh pengguna dienkripsi menggunakan Vigenère Cipher dengan username sebagai kunci.
-Password terenkripsi hasil dari input pengguna dibandingkan dengan password terenkripsi yang tersimpan di database.
-Jika kedua password terenkripsi cocok, maka login berhasil. Jika tidak, login gagal.
