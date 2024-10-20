# BIODATA
# NAMA: MARSYA NABILA PUTRI
# KELAS TI.24.A.4
# NIM: 312410338
# MATKUL: BAHASA PEMROGRAMAN 
![WhatsApp Image 2024-10-20 at 10 55 01_a29547f6](https://github.com/user-attachments/assets/025ddb8a-7dfd-4b60-a805-4e2cb48b4199)
# LATIHAN 1
![WhatsApp Image 2024-10-20 at 14 26 18_a82c4f79](https://github.com/user-attachments/assets/983f823f-b61c-4cd8-8c08-fb1a770e1444)
# PEMBAHASAN MENGENAI:
# PENGGUNAAN END
# PENGGUNAAN SEREPATOR
# STRING FORMAT
# PENGGUNAAN END
![WhatsApp Image 2024-10-20 at 14 27 49_9caf21d0](https://github.com/user-attachments/assets/d9f11408-f12d-4988-a024-204d97c3e596)
```PYTHON
print('A', end='')
print('b', end='')
print('c', end='')
print()
print('x')
print('y')
print('z')
````
Parameter end dalam fungsi Print () di python di gunakan untuk menambahkan string(" ")apapun diakhir dan mengeluarkan pertanyaan print
```PYTHON
Print()
````
Secara default,fungsi print() akan mengakhiri dengan baris baru,dan akan secara otomatis karakter baris baru di akhir outputnya

inilah hasil program tersebut:

![WhatsApp Image 2024-10-20 at 14 45 20_8564751e](https://github.com/user-attachments/assets/1b01bff3-22e9-459a-84a0-60b29ba656c4)

dan ini hasil tanpa menggunakan fungsi print() di tengah pada kode program di atas:

![WhatsApp Image 2024-10-20 at 14 45 30_d59d567c](https://github.com/user-attachments/assets/404ebc53-85b5-4d72-87d3-34546677511a)

# PENGGUNAAN SEREPATOR


![WhatsApp Image 2024-10-20 at 14 50 38_602436da](https://github.com/user-attachments/assets/c4c13d67-81fc-4f1a-98ec-40a2d0e72691)
```PYTHON
w, x, y, z, =10, 15, 20, 25
print(w, x, y, z,)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```

pada python penggunaan serepator dapat menggunakan fungsi split() atau sep yang seperti dalam kode program di atas

serepator ini menentukan pembatasan yang digunakan untuk memisahkan sting,serepator dapat berupa karakter tunggal atau beberapa karakter.jika tidak ditentukan,maka python akan menggunakan spasi sebagai pemisah.

Berikut Hasil Kode Program Diatas:

![WhatsApp Image 2024-10-20 at 14 56 38_fec5a7eb](https://github.com/user-attachments/assets/ee1b71a8-6002-4bda-bad1-8564c50ad180)

```PYTHON
w, x, y, z, =10, 15, 20, 25
````
Variable yang seperti ini menentukan parameter,jadi variable ini tidak bisa memasukan variable angka yang sudah ditentukan w = 10,x=15,y=20,z=25

```PYTHON
print(w, x, y, z,)
````
Fungsi ini hanya mencetak saja yang menggunakan fungsi print(), tetapi di karenakan mencetak parameter,koma tersebut di hilangkan

```PYTHON
print(w, x, y, z, sep=',')
````

karena pemisahnya dihilangkan,kita menggunakan fungsi sepatausplit()dan kita memasukkan pemisahnya didalam string akan memunculkan cetakan yang sesuai keinginan anda dalam memisahkan sesuatu parameter

# STRING FORMAT
![WhatsApp Image 2024-10-20 at 15 05 47_b2d94640](https://github.com/user-attachments/assets/ca7154c5-aba7-4612-8f6b-0c0e9ff256ef)

```PYTHON
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````
String Format adalah proses memasukan variable atau string kustom ke dalam teks yang sudah ditentukan,dan dapat digunakan untuk berbagai keperluan,seperti memasukan judul dalam grafik,menampilkan pesan atau kesalahan, atau meneruskan kesalahan ke suatu fungsi

```PYTHON
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
````

Nilai pertama dalam setiap pasangan adalah angka dari 0 hingga 10, kode program ini dihitung dengan menggunakan operasi pangkat atau fungsinya () untuk menaikkan 10 ke pangkat yang sesuai dengan angka pertama, yang bisa di bahasa manusiakan variable 0 = 10 pangkat 0, variable 1 10 pangkat 1 dan seterusnya hingga variable 10 yaitu 10 pangkat 10, dan di cetak dengan fungsi print()

```PYTHON
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````
Kode ini mencetak 11 baris dengan format {0:3} {1:16} yang di gunakan untuk mengatur format string

Pada string pertama, angka 0 di format untuk memeliki lebar 3 karakter atau yang bisa disebut 3 kali spasi dengan perataan kanan.

angka 1 diformat untuk memiliki lebar 16 Karakter atau 16 kali spasi dengan perataan kanan, dan masing-masing mencetak nilai seperti format di atas dengan fungsi print()

# KODE PROGRAM
# 3 INPUT BILANGAN

```PYTHON
a = int(input("masukan angka pertama: "))
b = int(input("masukan angka kedua: "))
c = int(input("masukan angka ketiga: "))

if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
elif b > a and b > c:
    print(f"angka lebih besar adalah {b}")
else:
    print(f"angka lebih besar adalah {c}")
````
Program ini akan menginputkan 3 bilangan dari a yang sampai dengan c.

```PYTHON
if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
````
Karna Jika {a} lebih besar dari {b} dan {a} lebih besar dari {c}, output yang keluar adalah {a}

```PYTHON
elif b > a and b > c:
   print(f"angka lebih besar adalah {b}")
````
dan jika {b} lebih besar dari {a} dan {b} lebih besar dari {c} maka output yang keluar adalah {b}

```PYTHON
else:
    print(f"angka lebih besar adalah {c}")
````
Jika inputan yang diatas lebih kecil dari {c} maka output {c} yang akan keluar

Ini adala hasil program tersebut :

![WhatsApp Image 2024-10-20 at 15 32 56_30c926cd](https://github.com/user-attachments/assets/cdcdf5e7-4ae7-4873-8e59-5f5bf554f5c0)

dengan eksekusi program:
![WhatsApp Image 2024-10-20 at 15 35 28_0ace3926](https://github.com/user-attachments/assets/15fb9451-576f-4151-88be-bc5244dae24d)

































