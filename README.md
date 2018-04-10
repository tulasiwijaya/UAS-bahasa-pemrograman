  #Program ini menggunakan Python 3.4 GUI 64 bit
  
##program ini akan menampilkan beberapa pilihan, diantaranya pilihan kalkulator, penilaian mahasiswa, dan  pembayaran mahasiswa yang telah di susun dengan menggunakan beberapa syntax.Dalam program ini juga di lengkapi dengan password untuk login,dengan tampilan password yang tidak di tampilkan di layar namun tetap terbaca di filenya. Berikut beberapa penjelasan mengenai syntax yang ada pada program tersebut dan cara untuk runing  di pyton.

##import getpass
syntax ini berfungsi untuk menyamarkan passowrd agar ketika kita masukkan pasword tidak terlihat di layar monitor. berikut syntaxnya
```javascript
import getpass
username = input("\nUsername : ")
password = getpass.getpass()
```
#contohnya adalah : 
```javascript
if username == "tulasi" and password == "12345" :
    login()

else :
    print("Maaf username atau password kamu salah")
```
##berikut adalah syntaxn untuk input menu pilihan utama :
```javascript
def login():
    print("=============================================")
    print("\n\t----Menu Utama-----")
    print("\t1. Kalkulator")
    print("\t2. pembayaran_mahasiswa")
    print("\t3. penilaian_mahasiswa")
		pilih = input("\n\tSilahkan Pilih : ")
```
##Hasil outputnya sebagai berikut : 
```javascript
	----Menu Utama-----
	1. Kalkulator
	2. pembayaran_mahasiswa
	3. penilaian_mahasiswa

	Silahkan Pilih : 
```







```javascript
def tanya():
    tanya = input("\nKembali Ke menu (y/n) ?")
    if tanya == "y":
        login()
    elif tanya == "n":
        exit
    else:
        print("\n\tSalah Input !!")
```
