# Aplikasi Konversi Suhu

## Deskripsi
Aplikasi Konversi Suhu adalah program yang memungkinkan pengguna untuk memasukkan nilai suhu dalam satu skala dan mengonversinya ke skala lain. Pengguna dapat memilih antara Celsius, Reamur, Fahrenheit, dan Kelvin. Hasil konversi akan ditampilkan setelah tombol konversi ditekan.

## Fitur
- **Input Suhu**: Pengguna dapat memasukkan nilai suhu yang ingin dikonversi.
- **Pilihan Skala**: Pengguna dapat memilih skala suhu yang diinginkan untuk konversi.
- **Hasil Konversi**: Hasil konversi ditampilkan secara langsung setelah tombol konversi ditekan.
- **Validasi Input**: Program membatasi input hanya untuk angka agar menghindari kesalahan.

## Komponen GUI
Aplikasi ini dibangun menggunakan komponen GUI Java Swing, termasuk:
- `JFrame`: Jendela utama aplikasi.
- `JPanel`: Panel untuk mengatur layout.
- `JLabel`: Untuk menampilkan teks dan label.
- `JTextField`: Untuk input nilai suhu dari pengguna.
- `JComboBox`: Untuk memilih skala suhu.
- `JButton`: Tombol untuk melakukan konversi.

## Logika Program
Program menggunakan rumus konversi suhu berikut:
- Celsius ke Fahrenheit: \( F = C \times \frac{9}{5} + 32 \)
- Reamur ke Celsius: \( C = R \times \frac{5}{4} \)
- Fahrenheit ke Celsius: \( C = (F - 32) \times \frac{5}{9} \)
- Kelvin ke Celsius: \( C = K - 273.15 \)

## Cara Menggunakan
1. Masukkan nilai suhu pada kolom input.
2. Pilih skala suhu dari dropdown yang tersedia.
3. Klik tombol "Konversi" untuk melihat hasilnya.

## Instalasi
1. Clone repositori ini ke komputer Anda:
   ```bash
   git clone https://github.com/Ikyisaboy/AplikasiKonversiSuhu.git
