sayi=int(input("Collatz hesabı yapmak istediğininz sayıyı girin"))
adimsayisi=0
while sayi!=1:
    adimsayisi+=1
    if sayi%2==1: #sayı tekse
        sayi = sayi*3+1
        print(sayi)#sayının yeni değeri
    else:#sayi çiftse
        sayi=sayi//2
        print(sayi)#sayının yeni değeri
print("hesaplama",adimsayisi,"adımda tamamlandı")
