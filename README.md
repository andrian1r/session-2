# 📘 Basic Python Data Types & Indexing

## 📖 Overview

This project demonstrates fundamental Python concepts for beginners.  
It covers indexing, core data types, numeric formatting, and simple structured data output.

The script helps students understand how Python handles different variable types and how indexing works in strings, lists, and tuples.

---

## 🚀 Topics Covered

- String indexing (including negative indexing)
- List indexing
- Data types:
  - `str` (String)
  - `int` (Integer)
  - `float` (Decimal number)
  - `bool` (Boolean)
- Type checking using `type()`
- Numeric formatting using underscores
- Tuple usage
- Basic formatted output

---

## 🧠 Example Code

```python
# String indexing
huruf = "Hello"
print(huruf[-1])

# List indexing
angka = [1, 2, 3, 4, 5]
print(angka[-1])

# Data types
panjang = "besi"
print(type(panjang))

umur = 100
print(type(umur))

print(111_111_111)

nilai_pts_mtk = 8.5
print(type(nilai_pts_mtk))

berhasil = True
gagal = False
print(type(berhasil))

# Biodata example
nama = ("andrian", "wijaya", "santoso")
umur = 13
tinggi = 1.50
hobby = ("maen game", "basket")

print("====Biodata andrian====")
print("nama:", nama[0], nama[2], nama[1])
print("umur:", umur, "tahun")
print("tinggi:", tinggi, "m")
print("hobi:", hobby[0])
```

---

## 🖥 Example Output

```
o
5
<class 'str'>
<class 'int'>
111111111
<class 'float'>
<class 'bool'>
====Biodata andrian====
nama: andrian santoso wijaya
umur: 13 tahun
tinggi: 1.5 m
hobi: maen game
```

---

## 🎯 Purpose

This project is intended for:

- Beginner Python learners
- Students practicing programming basics
- Understanding indexing and type systems in Python

---

## 🛠 Requirements

- Python 3.x

---

## 👤 Author

Andrian Wijaya

---

## 📜 License

This project is created for educational purposes.
