
# TUGAS JS SKILVUL

tugas ini adalah tugas yang diberikan oleh kak 
Arief Faltah sebanyak 5 soal untuk coba dikerjakan sebagai latihan. 

# Penjelasan Soal No 1

Kode pada soal nomor 1 merupakan sebuah halaman HTML yang berisi kode JavaScript yang melakukan perulangan dengan for loop sebanyak 100 kali, dimulai dari angka 1 hingga 100. 

Setiap kali perulangan dilakukan, teks "User ke -" dan nomor urut perulangan (i) akan ditampilkan di halaman HTML menggunakan metode document.write(), diikuti dengan tag <br> untuk membuat baris baru. 

Dengan demikian, halaman HTML akan menampilkan 100 baris teks, masing-masing berisi "User ke - 1", "User ke - 2", dan seterusnya hingga "User ke - 100".

# Penjelasan Soal No 2

Kode pada soal nomor 2 merupakan sebuah program yang menggunakan perulangan for loop untuk melakukan penambahan nilai sebanyak 10 kali, dimulai dari nilai awal 0 dan setiap iterasi nilai awal akan ditambahkan 2.

Variabel nilaiAwal diinisialisasi dengan nilai 0. Kemudian, program akan melakukan pengulangan dengan menggunakan for loop dari i = 1 hingga i <= 10.

Pada setiap iterasi, nilai variabel nilaiAwal akan diupdate dengan menambahkan nilai 2. Kemudian, program akan menampilkan pesan dengan format Nilai pada pengulangan ke-i: nilaiAwal. Pesan ini akan ditampilkan di console log.

# Penjelasan Soal No 3

Kode pada soal nomor 3 merupakan pengulangan dengan menggunakan for loop. Loop akan melakukan iterasi dari 0 sampai dengan 20. Pada setiap iterasi, dilakukan pengecekan apakah nilai tersebut genap atau ganjil dengan menggunakan operator modulo (%). Jika hasil modulo dari nilai i dengan angka 2 adalah 0, maka nilai tersebut adalah bilangan genap, dan jika hasil modulo tidak sama dengan 0, maka nilai tersebut adalah bilangan ganjil.

Kemudian, untuk setiap nilai i yang diperiksa, akan dicetak pada console dengan menambahkan keterangan apakah bilangan tersebut ganjil atau genap. Jika nilai i genap, maka keterangan yang dicetak adalah "i adalah bilangan genap", sedangkan jika nilai i ganjil, maka keterangan yang dicetak adalah "i adalah bilangan ganjil".

# Penjelasan Soal No 4

Kode pada soal nomor 4 menggunakan perulangan while dengan kondisi awal repeat = true. Program akan terus mengeksekusi blok kode di dalam perulangan while hingga kondisi repeat bernilai false. Pada setiap iterasi, program akan menampilkan pop up konfirmasi menggunakan fungsi confirm(). Jika user memilih OK, variabel count akan diincrement. Jika user memilih Cancel, variabel repeat akan diubah menjadi false dan program akan menampilkan alert dengan pesan "Perulangan sudah dilakukan sebanyak (jumlah klik OK yang dilakukan user)".

# Penjelasan Soal No 5

Kode pada soal nomor 5 merupakan program kuis sederhana dengan menggunakan perulangan while loop dan prompt() untuk meminta input dari user. Program akan terus menampilkan prompt() dengan pertanyaan "Sebutkan kepanjangan dari nama IB (Impact Byte)?" hingga jawaban dari user sesuai dengan yang diharapkan.

Dalam kode tersebut, variabel answer digunakan untuk menyimpan jawaban yang diinputkan oleh user. Pada awalnya, nilai variabel answer diberikan nilai string kosong. Selama nilai answer yang diinputkan user tidak sama dengan string "Impact Byte" (tanpa case sensitive), program akan terus menampilkan prompt() dengan pertanyaan yang sama dan meminta input dari user.

Ketika user akhirnya memberikan jawaban yang sesuai yaitu "Impact Byte", maka program akan menghentikan perulangan dan menampilkan pesan "Selamat jawaban kamu benar!" menggunakan alert().