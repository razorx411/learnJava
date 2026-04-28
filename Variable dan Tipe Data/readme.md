# 📘 Java Data Types (Tipe Data Dasar)

Dokumen ini berisi penjelasan singkat mengenai tipe data dasar di Java seperti `String`, `int`, `double`, `float`, dan lainnya.

---

## 🔹 1. String

`String` digunakan untuk menyimpan teks atau kumpulan karakter.

### Contoh:

```java
String nama = "Razor";
```

### Penjelasan:

* Ditulis dengan tanda kutip `" "`
* Termasuk tipe data **non-primitive (object)**

---

## 🔹 2. int

`int` digunakan untuk menyimpan bilangan bulat (tanpa desimal).

### Contoh:

```java
int umur = 18;
```

### Penjelasan:

* Range: -2,147,483,648 sampai 2,147,483,647
* Tipe data **primitive**

---

## 🔹 3. float

`float` digunakan untuk bilangan desimal (presisi rendah).

### Contoh:

```java
float tinggi = 171.5f;
```

### Penjelasan:

* Harus pakai `f` di akhir angka
* Presisi: sekitar 6-7 digit
* Tipe data **primitive**

---

## 🔹 4. double

`double` digunakan untuk bilangan desimal (presisi tinggi).

### Contoh:

```java
double berat = 67.25;
```

### Penjelasan:

* Default untuk angka desimal
* Presisi: sekitar 15 digit
* Tipe data **primitive**

---

## 🔹 5. char

`char` digunakan untuk menyimpan satu karakter.

### Contoh:

```java
char grade = 'A';
```

### Penjelasan:

* Ditulis dengan tanda kutip satu `' '`
* Hanya 1 karakter

---

## 🔹 6. boolean

`boolean` digunakan untuk nilai benar atau salah.

### Contoh:

```java
boolean lulus = true;
```

### Penjelasan:

* Hanya ada 2 nilai: `true` atau `false`

---

## 🔹 7. long

`long` digunakan untuk bilangan bulat besar.

### Contoh:

```java
long populasi = 8000000000L;
```

### Penjelasan:

* Harus pakai `L` jika angka besar
* Range lebih besar dari `int`

---

## 🔹 8. short

`short` digunakan untuk bilangan bulat kecil.

### Contoh:

```java
short angkaKecil = 1000;
```

---

## 🔹 9. byte

`byte` digunakan untuk bilangan sangat kecil.

### Contoh:

```java
byte data = 127;
```

---

## 🧠 Kesimpulan

Java memiliki dua jenis tipe data:

* **Primitive** → int, float, double, char, boolean, dll
* **Non-Primitive** → String, Array, Object, dll

Pemilihan tipe data penting untuk:

* Menghemat memori
* Meningkatkan performa
* Menghindari error saat coding

---

## 🚀 Tips

* Gunakan `int` untuk angka biasa
* Gunakan `double` untuk desimal (lebih aman)
* Gunakan `float` jika butuh hemat memori
* Gunakan `String` untuk teks

---

✍️ Dibuat oleh Hafid Fathurrohman
