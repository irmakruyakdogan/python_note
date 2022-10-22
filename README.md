# basic exercises
#yarı çapı 7 olan dairenin alanını bulma
pi = 3.14
r = 7
print(pi * r **2)

#uzun ve kısa kenarı bilinen dikdörtgenin alanını bulma
a = 15 #kısa kenar
b = 30 #uzun kenar
print(a * b)

#string örnek 41 kere maşallah tüh
x = 'masallah'
def cokluyazdir(sayi, yazilansayi):
    for i in range(sayi):
        print(yazilansayi)
        
cokluyazdir(41, x)

kader = "kendim, ettim, kendim, buldum, gul, gibi, sararip, soldum"
print(len(kader))  #kaç karakterden oluştuğunu gösteriyor
print(kader[7:31])
print(kader[2:56:3])

#veri dönüştürme
a = "yirmagh"
print(type(a))

x = 5+2
print(type(x))

y = 5.2
print(type(y))  

#bazı gömülü fonksiyonlar int, float, str, type, len

a = int(input("sayi: "))
if (a % 2 ==0):
    print("sayi çifttir.")
else:
    print("sayi tektir.")
