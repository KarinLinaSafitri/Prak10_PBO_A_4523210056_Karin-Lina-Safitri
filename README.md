Tugas
1.	Tambahkan fitur Ubah PIN
a.	Tambahkan opsi “Ubah PIN” pada menu utama
 ![image](https://github.com/user-attachments/assets/3d9eac52-5692-4fea-8797-2bc15f3920ea)

  Menambahkan opsi Ubah pin pada kelas ATM.java , bagian showMenu(Account account) telah diperbarui untuk menampilkan opsi “Ubah PIN” sebagai pilihan nomor 5.
  
b.	Buat mdeo dalam kelas Account untuk mengubah PIN, yaitu: changePin()
 ![image](https://github.com/user-attachments/assets/332da75b-64d7-4d20-8132-469b83f6761f)

   Di dalam kelas ATM, metode changePin(Account account) dipanggil ketika pengguna memilih opsi "Ubah PIN" di menu utama.
   
c.	Dalam method tersebut lakukan hal berikut:
i.	Verifikasi PIN lama
ii.	Minta nasabah memasukkan PIN baru dua kali
iii.	Validasi bahwa kedua input PIN baru cocok
iv.	Perbarui PIN jika validasi berhasil
![image](https://github.com/user-attachments/assets/08dbfd58-d3aa-4ef1-a944-4742b73ed1ba)

   Memverifikasi PIN lama, meminta dua input untuk PIN baru, memastikan bahwa kedua input cocok, dan memperbarui PIN jika semua validasi berhasil.
   
2.	Validasi Saldo Minimal pada saat penarikan
a.	Modifikasi fitur penarikan sehingga nasabah harus menyisakan saldo minimal setelah penarikan dilakukan. Misal, saldo minial adalah Rp50,000-
 ![image](https://github.com/user-attachments/assets/6e9b5e29-275c-4af3-845b-b10267eff937)

b.	Langkah-langkah:
i.	Tentukan saldo minimal, tambahkan konstanta MINIMUM_BALANCE dalam kelas Account
 ![image](https://github.com/user-attachments/assets/38a8b8ac-2125-48b2-8e0d-39149988f839)

   Untuk mengetahui saldo minimal, tambahkan konstanta MINIMUM_BALANCE ke dalam kelas Account. Misalnya, jika saldo minimal ditetapkan sebesar Rp50,000, tambahkan baris berikut ke dalam kelas Account.
ii.	Modifikasi methode execute() dalam kelas Withdrawal untuk memeriksa apakah saldo setelah penarikan tidak kuran dari saldo minimal
 ![image](https://github.com/user-attachments/assets/2b72b8a3-726b-4ca9-8447-1121bdb6f17d)

	Menambahkan metode execute() di kelas Withdrawl untuk memeriksa apakah saldo setelah penarikan tidak kurang dari saldo minimal.
