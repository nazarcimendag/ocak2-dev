# 1.
sayi = int(input("Bir sayı girin: "))

if sayi % 2 == 0:
    print(f"{sayi} sayısı çifttir.")
else:
    print(f"{sayi} sayısı tektir.")

# 2.
notu = int(input("Notunuzu girin: "))

if 90 <= notu <= 100:
    print("Harf notunuz: A")
elif 80 <= notu <= 89:
    print("Harf notunuz: B")
elif 70 <= notu <= 79:
    print("Harf notunuz: C")
elif 60 <= notu <= 69:
    print("Harf notunuz: D")
elif 0 <= notu <= 59:
    print("Harf notunuz: F")
else:
    print("Geçersiz not!")


# 3.
yas = int(input("Yaşınızı girin: "))


if 0 <= yas <= 12:
    print("Yaş grubunuz: Çocuk")
elif 13 <= yas <= 19:
    print("Yaş grubunuz: Genç")
elif 20 <= yas <= 59:
    print("Yaş grubunuz: Yetişkin")
elif yas >= 60:
    print("Yaş grubunuz: Yaşlı")
else:
    print("Geçersiz yaş!")
