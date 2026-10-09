# Latihan Python Dasar

Tugas Machine Learning: menjalankan setiap latihan dari slide **Python Dasar** (bab 01-11).

Setiap folder bab berisi file latihan yang sudah dijalankan. Di bawah ini adalah hasil output dari tiap latihan.

## Cara menjalankan

Contoh menjalankan satu latihan (dari folder utama):

```
cd bab05
python grade.py
```

Khusus bab11, jalankan dari dalam folder `bab11` karena kodenya membaca `nilai.csv`.

---

## Bab 01 - Pengenalan Python

**hello.py**
```
Halo, Dunia!
Indentasi = blok kode
Gunakan 4 spasi
```

## Bab 02 - Variabel & Tipe Data

**variabel.py**
```
Budi 21 6
```

**casting.py**
```
30
<class 'float'>
Umur: 20
False True
```

**string.py**
```
12
PYTHON DASAR
Python
['Python', 'Dasar']
Belajar Python Dasar bab 2
```

## Bab 03 - Input & Output

**output.py**
```
Halo Dunia
A-B-C
Loading...selesai
Harga: Rp2142.86
Total: 1,500,000
```

**input.py** (input: `Sari` dan `19`)
```
Siapa namamu? Sari
Berapa umurmu? 19
Halo Sari!
Tahun depan kamu 20 tahun
```

## Bab 04 - Operator

**logika.py**
```
True
False
False
```

**operator.py**
```
30
True
True
True
```

## Bab 05 - Percabangan

**if_else.py**
```
Selamat, kamu lulus!
Program selesai
```

**grade.py**
```
Nilai 78 → grade B
```

**nested.py**
```
Boleh memilih
```

**ternary.py**
```
anak
```

**match.py**
```
Libur!
```

## Bab 06 - Perulangan

**for_loop.py**
```
Putaran ke-1
Putaran ke-2
Putaran ke-3
APEL
JERUK
MANGGA
```

**while_loop.py**
```
Hitung mundur: 3
Hitung mundur: 2
Hitung mundur: 1
Meluncur!
```

**kontrol.py**
```
1
2
4
5
```

## Bab 07 - List, Tuple, Set & Dictionary

**list.py**
```
[85, 90, 75]
75 3
[75, 85, 90]
```

**tuple.py**
```
x=3, y=7
255 3
Traceback (most recent call last):
  ...
TypeError: 'tuple' object does not support item assignment
```
Error di akhir memang disengaja: tuple bersifat immutable (tidak bisa diubah).

**set.py**
```
{1, 2, 3}
{'Ani', 'Budi', 'Dodi', 'Citra'}
{'Budi'}
{'Ani', 'Citra'}
```
Urutan isi set bisa berbeda tiap dijalankan, karena set tidak berurutan.

**dictionary.py**
```
Sari
-
nama: Sari
umur: 20
kota: Bandung
```

## Bab 08 - Function

**function.py**
```
15
20
```

**parameter.py**
```
Halo, Ani!
Hai, Budi!
10
```

**lambda.py**
```
16
('Budi', 95)
```

**scope.py**
```
lokal
global
```

## Bab 09 - Error Handling

**try_except.py** (input: `0`)
```
Masukkan angka: 0
Tidak bisa dibagi nol!
Selesai.
```

**raise.py**
```
Error: Umur tidak valid
```

## Bab 10 - Module & Package

**pakai_module.py**
```
4.0
3.141592653589793
4
2026
```
Angka pada baris ketiga acak (1 sampai 6), jadi bisa berbeda tiap dijalankan.

**proyek/main.py**
```
80.0
```

Struktur package:
```
bab10/
├── pakai_module.py
└── proyek/
    ├── main.py
    └── utils/
        ├── __init__.py
        ├── hitung.py
        └── teks.py
```

Virtual environment (pip dan venv) dijalankan lewat terminal, daftar paketnya tersimpan di `requirements.txt`.

## Bab 11 - Pengolahan Data Sederhana

**baca_data.py**
```
5 baris
{'nama': 'Ani', 'kelas': 'A', 'nilai': 85}
```

**olah_data.py**
```
Rata-rata: 78.4
Lulus: ['Ani', 'Citra', 'Eka']
Tertinggi: Citra
```

**rekap.py**
```
Kelas   Jumlah    Rata
A            3    85.3
B            2    68.0
```

**pakai_pandas.py**
```
kelas
A    85.333333
B    68.000000
Name: nilai, dtype: float64
['Ani', 'Citra', 'Eka']
    nama kelas  nilai
2  Citra     A     93
```
