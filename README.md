# Matematik-Not-Sistemi
İsim = str(input("Adınızı Giriniz:"))
print("İsim:", İsim)
Soyisim = str(input("Soyisminizi Giriniz:"))
print("Soyisim:", Soyisim)
Okul_No = int(input("Okul Numaranızı Giriniz:"))
print("Okul No:", Okul_No)
Sınav_Puanı = int(input("Sınav Puanını Giriniz:"))
print("Sınav Puanı:", Sınav_Puanı)

   
if Sınav_Puanı < 0:
    print("Notunuz Negatif Olamaz")
else:
    if 0 <= Sınav_Puanı <=49:
        Sınav_Puanı ="Kaldı Sınav Notu FF"
    elif 50 < Sınav_Puanı <= 59:
        Sınav_Puanı = "Kaldı Sınav Notu FD"
    elif 60 < Sınav_Puanı <=64:
        Sınav_Puanı = "Keçdi Sınav Notu DD"
    elif 65 < Sınav_Puanı <=69:
        Sınav_Puanı = "Keçdi Sınav Notu DC"
    elif 70 < Sınav_Puanı <=74:
        Sınav_Puanı = "Keçdi Sınav Notu CC"
    elif 75 < Sınav_Puanı <=79:
        Sınav_Puanı = "Keçdi Sınav Notu CB"
    elif 80 < Sınav_Puanı <=84:
        Sınav_Puanı = "Keçdi Sınav Notu BB"
    elif 84 < Sınav_Puanı <=89:
        Sınav_Puanı = "Keçdi Sınav Notu BA"
    elif 90 < Sınav_Puanı <=100:
        Sınav_Puanı = "Keçdi Sınav Notu AA"
print(f"Not Bilgisi: = {Sınav_Puanı}")
