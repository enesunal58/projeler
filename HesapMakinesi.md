print("Hesap Makinesi")
print("==============")
print("Aşağıdaki işlem numaralarından birini giriniz")
print("1-Toplama")
print("2-Çıkarma")
print("3-Çarpma")
print("4-Bölme")
secim = input("Seçiminiz:")
if secim == '1':
    sayi1 = int(input("1. Sayı: "))
    sayi2 = int(input("2. Sayı: "))
    print(sayi1 + sayi2)
if secim == '2':
    sayi1 = int(input("1. Sayı: "))
    sayi2 = int(input("2. Sayı: "))
    print(sayi1 - sayi2)
if secim == '3':
    sayi1 = int(input("1. Sayı: "))
    sayi2 = int(input("2. Sayı: "))
    print(sayi1 * sayi2)
if secim == '4':
    sayi1 = int(input("1. Sayı: "))
    sayi2 = int(input("2. Sayı: "))
    print(sayi1 / sayi2)
