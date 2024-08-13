# Phython_calculator-app2
import math
menu ="""
1)Topla
2)Çıkar
3)Çarp
4)Böl
5)Üstünü Hesapla
6)Karekökünü Hesapla
q)çıkış
"""

print(menu)
control= True
while control:
    işlem = input("İşlemi seçiniz:")

    if işlem == "q":
       print("Programdan çıkılıyor") 
       control = False
    elif işlem == "1":
        print("Toplama işlemi seçildi")
        print("-" * 30)
        topla1 = int(input("İlk sayıyı giriniz"))   
        topla2 = int(input("İkinci sayıyı giriniz"))   
        print("{} + {} = {}".format(topla1,topla2,topla1+topla2))
        print("-" * 30)
    elif işlem == "2":
        # phython calculator.py
        print("Çıkarma işlemi seçildi")
        print("-" * 30)
        çıkar1 = int(input("İlk sayıyı giriniz"))   
        çıkar2 = int(input("İkinci sayıyı giriniz"))   
        print("{} - {} = {}".format(topla1,topla2,çıkar1-çıkar2))
        print("-" * 30)
    elif işlem == "3":
        print("Çarpma işlemi seçildi")
        print("-" * 30)
        çarp1 = int(input("İlk sayıyı giriniz"))   
        çarp2 = int(input("İkinci sayıyı giriniz"))   
        print("{} x {} = {}".format(çarp1,çarp2,çarp1*çarp2))
        print("-" * 30)
    elif işlem == "4":
        print("Bölme işlemi seçildi")
        print("-" * 30)
        böl1 = int(input("İlk sayıyı giriniz"))
        böl2 = int(input("İkinci sayıyı giriniz"))
        print("{} / {} = {}".format(böl1,böl2,böl1/böl2))
        print("-" * 30)
    elif işlem == "5":
        print("Karesini alma")
        print("-" * 30)
        karesi1 = int(input("İlk sayıyı giriniz"))   
        karesi2 = int(input("İkinci sayıyı giriniz"))   
        print("{} ** {} = {}".format(karesi1,karesi2,karesi2**karesi1))
        print("-" * 30)
    elif işlem == "6":
        print("Karekökü alma")
        print("-" * 30)
        karekök1 = int(input("Sayıyı giriniz"))
        print("Karekökü: ", math.sqrt(karekök1))
        print("-" * 30)
