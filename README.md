# 1.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari 3 bilangan yang diinputkan
Berikut adalah flowchart nya  
![IMG-20241027-WA0031](https://github.com/user-attachments/assets/8b94451b-2ea4-4f10-b4a1-ae3d4ff8c491)
![Screenshot_20241027_195604_Chrome](https://github.com/user-attachments/assets/e883699a-60b2-4361-b574-d53b6448432b)
Input bilangan
Pengguna diminta untuk memasukkan tiga bilangan satu per satu. Nilai yang dimasukkan akan dikonversi menjadi tipe data float, yang memungkinkan pengguna memasukkan angka desimal.

Penggunaan (if-elif-else):

-if a > b and a > c: Kondisi ini mengecek apakah a lebih besar dari b dan c. Jika benar, maka a adalah bilangan terbesar, dan program mencetak hasilnya.

-elif b > a and b > c: Jika kondisi pertama salah, maka program akan mengecek apakah b lebih besar dari a dan c. Jika benar, maka b adalah bilangan terbesar.

-else: Jika kedua kondisi di atas salah, maka c yang dianggap sebagai bilangan terbesar.

Output

![Screenshot_20241027_190830_Chrome](https://github.com/user-attachments/assets/4951643d-e018-4f78-9be8-49968fdeeb9b)


# 2.) Buat codingan dari flowchart yang menentukan bilangan terbesar dari N bilangan yang diinputkan. untuk menentukan jumlah N, berikan masukkan angka 0

Berikut adalah flowchart nya  
![IMG-20241027-WA0030](https://github.com/user-attachments/assets/010a8864-c29c-4abc-b9b0-742c073f786a)
![Screenshot_20241028_075809_Chrome](https://github.com/user-attachments/assets/3385ed0e-42d0-49bc-a853-683f2f89b1ae)
Inisialisasi Variabel terbesar = float('-inf')

variabel terbesar diinisialisasi dengan nilai negatif tak terhingga (-inf). Ini dilakukan agar setiap bilangan yang dimasukkan oleh pengguna akan lebih besar dari nilai ini pada awalnya.
Input Jumlah Bilangan n = int(input("masukkan jumlah bilangan (N) atau 0 untuk mengakhiri: "))

Program meminta pengguna untuk memasukkan jumlah bilangan yang ingin dimasukkan. Pengguna dapat memasukkan angka positif untuk menentukan jumlah bilangan atau 0 untuk mengakhiri program.
Pengecekan Input Awal if n == 0: print("Tidak ada bilangan yang dimasukkan.") return

Jika pengguna memasukkan 0, program akan mencetak pesan bahwa tidak ada bilangan yang dimasukkan dan kemudian keluar dari fungsi dengan menggunakan return.
Perumusan dan Perbandingan for i in range(n): bilangan = float(input(f"masukkan bilangan ke-{i+1}: ")) if bilangan > terbesar: terbesar = bilangan

program akan melakukan iterasi sebanyak n kali. Pada setiap iterasi, pengguna diminta untuk memasukkan bilangan. Program kemudian membandingkan bilangan yang dimasukkan dengan nilai terbesar. Jika bilangan yang dimasukkan lebih besar dari terbesar, maka nilai terbesar akan diperbarui dengan bilangan tersebut.
Hasil Output print(f"bilangan terbesar adalah: {terbesar}")
![Screenshot_20241028_075151_Chrome](https://github.com/user-attachments/assets/9c000dae-6394-43a3-be36-a176691f6cf7)


Setelah semua bilangan dimasukkan dan dibandingkan, program akan mencetak bilangan terbesar yang ditemukan.
Pemanggilan Fungsi cari_terbesar_dari_n()

Terakhir, fungsi cari_terbesar_dari_n() dipanggil untuk menjalankan program.
