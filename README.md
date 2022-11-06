## Nama: Avrillia Nur Hidayah
## NIM: 312210309
## Kelas: TI.22.A3

# Praktikum-4

## LAB 2 Struktur Kondisi
### Latihan 1 (Program menentukan 2 bilangan terbesar)

```
a=int(input("masukkan angka pertama: "))
b=int(input("masukkan angka kedua:" ))
print()
if a>b:
    print (a,"adalah angka terbesar")
else:
    b>a
    print("angka terbesar:",b)
```

![Screenshot (609)](https://user-images.githubusercontent.com/115686359/199919376-1f7b7d57-07bb-471c-a3a9-ce057e080538.png)

### Latihan 2 (mengurutkan 3 variabel dari yang terkecil ke terbesar)

```
print("program mengurutkan data")
a = int(input("bilangan ke-1:"))
b = int(input("bilangan ke-2:"))
c = int(input("bilangan ke-3:"))

if a>b and a>c:
    if b>c:
        print("urutan bilangan:",c,b,a)
    else:
        print("urutan bilangan:",b,c,a)
elif b>a and b>c:
    if a>c:
        print("urutan bilangan:",c,a,b)
    else:
        print("urutan bilangan:",a,c,b)
else:
    if a>b:
        print("urutan bilangan:",b,a,c)
    else:
        print("urutan bilangan:",a,b,c)
```

![Screenshot (610)](https://user-images.githubusercontent.com/115686359/199923537-dcf865c6-eaa8-496d-8b81-f6ce6885cb11.png)

## LAB 3 Perulangan
### Latihan 1 (Bertingkat)

```
print("======lathan 1======")

print("masukkan nilai N:5")
import random
jumlah=5
a=0

for x in range(jumlah):
    i=random.uniform(.0,.5)
    a+=1
    print('data ke:',a,'==>',i)
print("=====SELESAI=====")
print("avrillia nur hidayah")
print("312210309")
```

![Screenshot (608)](https://user-images.githubusercontent.com/115686359/199923992-10ab4216-8b0b-4a86-a32c-84fc9608f08a.png)

### Latihan 2 (Lebih kecil dari 0.5)

```
max=0
while True:
    a=int(input ('masukkan bilangan ='))
    if max < a:
        max=a
    if a==0:
        break
print('bilangan terbesar adalah', max)
```

![Screenshot (606)](https://user-images.githubusercontent.com/115686359/199925030-09547248-c6d8-402e-bbe3-a738463eaff6.png)

## Modul Praktikum 2
### Tugas Praktikum 2 (nilai terbesar 2 angka)

```
a=int(input("masukkan angka pertama: "))
b=int(input("masukkan angka kedua:" ))
print()
if a>b:
    print (a,"adalah angka terbesar")
else:
    b>a
    print("angka terbesar:",b)
```

![Screenshot (609)](https://user-images.githubusercontent.com/115686359/199919376-1f7b7d57-07bb-471c-a3a9-ce057e080538.png)

## Modul Praktikum 3
### Latihan 1

```
print("======lathan 1======")

print("masukkan nilai N:5")
import random
jumlah=5
a=0

for x in range(jumlah):
    i=random.uniform(.0,.5)
    a+=1
    print('data ke:',a,'==>',i)
print("=====SELESAI=====")
print("avrillia nur hidayah")
print("312210309")
```

![Screenshot (606)](https://user-images.githubusercontent.com/115686359/200100569-813710bb-55fe-4214-b7d6-ae7f78558250.png)

### Latihan 2

```
max=0
while True:
    a=int(input ('masukkan bilangan ='))
    if max < a:
        max=a
    if a==0:
        break
print('bilangan terbesar adalah', max)
```

![Screenshot (613)](https://user-images.githubusercontent.com/115686359/200101109-3932bb09-10ab-4335-9aec-b9f89dea19b8.png)

### Program 1

```
a = 1000000000
for x in range (1,9):
    if(x>=1 and x<=2):
        b=a*0
        print('laba bulan ke-',x,'sebesar:',b)

    if(x>=3 and x<=4):
        c=a*0.1
        print('laba bulan ke-',x,'sebesar:',c)
    if(x >= 5 and x <= 7):
        d= a*0.5
        print('laba bulan ke-', x, 'sebesar:',d)
    if (x==8):
         e=a*0.2
         print('laba bulan ke-',x,'sebesar:',e)
total=b+b+c+c+d+d+d+e
print('/n total laba adalah:',total)
print("avrillia nur hiadayah")
print("NIM:312210309")
```

![Screenshot (611)](https://user-images.githubusercontent.com/115686359/200101167-c9b87b4b-e408-4f41-b5ac-ca8e7afb46a1.png)

# SELESAI.

