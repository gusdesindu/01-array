

#  Sistem Analisis Nilai Mahasiswa Menggunakan Array

## Deskripsi Program

Program ini dibuat menggunakan bahasa **Python** untuk mengelola dan menganalisis data nilai mahasiswa. Data nilai disimpan menggunakan struktur data **array**, kemudian dilakukan beberapa proses analisis seperti mencari nilai maksimum, nilai minimum, rata-rata nilai, serta menghitung jumlah mahasiswa yang lulus dan tidak lulus.

Selain itu, program juga menampilkan **visualisasi grafik** berupa grafik batang dan grafik pie untuk memperjelas hasil analisis data.

---

# 1️ Penjelasan Konsep Array

Array merupakan struktur data yang digunakan untuk menyimpan kumpulan data dengan tipe yang sama dalam satu variabel. Pada program ini, array digunakan untuk menyimpan nilai mahasiswa sehingga data dapat diproses dengan lebih mudah.

Pada bagian awal program digunakan **list Python** untuk menampung nilai yang diinput oleh pengguna.

```python
data_nilai = []
```

Nilai kemudian dimasukkan menggunakan perulangan.

```python
for i in range(10):
    angka = int(input(f"Input nilai ke-{i+1}: "))
    data_nilai.append(angka)
```

Setelah itu data diubah menjadi **array menggunakan library numpy** agar dapat diproses lebih efisien.

```python
array_nilai = np.array(data_nilai)
```

Array tersebut kemudian digunakan untuk melakukan berbagai perhitungan seperti:

* mencari nilai maksimum
* mencari nilai minimum
* menghitung rata-rata
* menentukan jumlah mahasiswa yang lulus

---

# 2️ Screenshot Hasil Eksekusi

Berikut merupakan hasil eksekusi program saat dijalankan.


Output program menampilkan:

* Data nilai mahasiswa
* Nilai maksimum
* Nilai minimum
* Rata-rata nilai
* Jumlah mahasiswa lulus dan tidak lulus
* Grafik perbandingan nilai
* Grafik persentase kelulusan

---

# 3️ Analisis Kompleksitas

Analisis kompleksitas waktu dari program ini dapat dijelaskan sebagai berikut:

### Input Data

Proses memasukkan nilai menggunakan perulangan sebanyak **n data**.

Kompleksitas waktu:

O(n)

### Perhitungan Nilai

Perhitungan seperti menghitung jumlah lulus, rata-rata, nilai maksimum, dan minimum juga membutuhkan iterasi terhadap seluruh data.

Kompleksitas waktu:

O(n)

### Pembuatan Grafik

Pembuatan grafik menggunakan **matplotlib** hanya menggunakan data yang sudah diproses sehingga kompleksitasnya relatif kecil dibanding proses input.

Secara keseluruhan kompleksitas program adalah:

O(n)

Hal ini berarti waktu eksekusi program akan meningkat secara linear sesuai jumlah data nilai yang dimasukkan.

---

# 4️ Refleksi Pembelajaran

Melalui pembuatan program ini saya dapat memahami bagaimana cara menggunakan struktur data **array** untuk menyimpan dan mengolah data dalam jumlah banyak. Saya juga belajar menggunakan **library numpy** untuk mengelola array serta **matplotlib** untuk membuat visualisasi data dalam bentuk grafik.

Selain itu, saya memahami bagaimana proses analisis data sederhana dapat dilakukan menggunakan pemrograman Python, seperti mencari nilai maksimum, minimum, rata-rata, serta menghitung jumlah kelulusan mahasiswa.

Pembelajaran ini membantu saya memahami penerapan struktur data dalam kasus nyata serta meningkatkan kemampuan dalam membuat program analisis data sederhana.

