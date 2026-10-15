# Praktikum Machine Learning - Data Loading

## Deskripsi
Project ini merupakan hasil praktikum Machine Learning dengan materi Data Loading.

Pada praktikum ini dilakukan proses membaca dan memuat dataset Housing Price yang memiliki file `train.csv` dan `test.csv` menggunakan Python dan library Pandas.

## Tujuan Praktikum
- Memahami cara melakukan Data Loading menggunakan file CSV.
- Mengetahui cara membaca dataset menggunakan Pandas.
- Memahami struktur dan isi data `train.csv` dan `test.csv`.
- Melakukan pengecekan awal terhadap dataset.

## Tools
- Python
- Pandas
- Jupyter Notebook / VS Code

## Dataset
Dataset yang digunakan adalah dataset Housing Price dengan:
- `train.csv` sebagai data training.
- `test.csv` sebagai data testing.

## Proses Praktikum
1. Mengimport library Pandas.
2. Membaca file `train.csv`.
3. Membaca file `test.csv`.
4. Menampilkan data menggunakan `head()`.
5. Mengecek jumlah baris dan kolom.
6. Mengecek struktur dan tipe data.
7. Mempersiapkan dataset untuk proses pengolahan selanjutnya.

## Kode Program

```python
import pandas as pd

train = pd.read_csv("train.csv")
test = pd.read_csv("test.csv")

print("Jumlah data train:", len(train))
print("Jumlah data test:", len(test))

print("Jumlah kolom train:", len(train.columns))
print("Jumlah kolom test:", len(test.columns))

print(train.head())
print(test.head())
