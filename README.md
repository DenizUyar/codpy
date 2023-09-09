# Toplama 
def toplama(x,y):
    return x + y
 
# Cıkarma
def cıkarma(x,y):
    return x - y

# Carpma
def carpma(x,y):
    return x * y

# Bolme
def bolme(x,y):
   if y==0:
       return "SIFIRA BÖLME HATASI"
       return x/y

print("Yapmak istediginiz islemi secin")
print("1.islem Toplama")
print("2.İslem Cıkarma")
print("3.İslem Carpma")
print("4.islem Bolme")

secim = input("İslem yapin (1/2/3/4): ")
sayi1 = float(input("birinci sayiyi girin: "))
sayi2 = float(input("İkinci sayıyı girin: "))
if secim == '1':
    print("Sonuç: ", toplama(sayi1, sayi2))
elif secim == '2':
    print("Sonuç: ", cikarma(sayi1,sayi2))
elif secim == '3':
    print("Sonuç: ", carpma(sayi1,sayi2))
elif secim == '4':
    print("Sonuç: ", bolme(sayi1,sayi2))
else:
    print("Geçersiz Giriş")
