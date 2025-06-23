# Kalkulator kod
a=int(input("1-sonni kriting : "))
b=int(input("2-sonni kriting : "))
print(f"Sonlar ko'paytmasi : {a*b}")
print(f"Sonlar bo'linmasi : {a/b}")
print(f"Sonlar yig'indisi : {a+b}")
print(f"Sonlar ayirmasi : {a-b}")







# if-else operatorlari yosh tekshirish
yosh = int(input("Yoshingizni kiriting: "))
if yosh >= 18:
    print("Siz voyaga yetgansiz.")
else:
    print("Siz voyaga yetmagansiz.")








    
    
# Tasodifiy raqam topish o‘yini



import random

sirli_son = random.randint(1, 10)
taxmin = int(input("1 dan 10 gacha son o'yladim. Topa olasizmi? "))

if taxmin == sirli_son:
    print("Zo‘r! To‘g‘ri topdingiz!")
else:
    print(f"Afsus, men {sirli_son} sonini o‘ylagan edim."





    
 # Do'stlarga xat kodi
 ism = input("Do‘stingizning ismini kiriting: ")
xat = f"""
Salom, {ism}!

Umid qilamanki, bugun sening kayfiyating a'lo!

Men Python o‘rganayapman va dastur orqali senga xat yozishni o‘yladim.
Bu juda qiziqarli, to‘g‘rimi? 😊

Yaxshi kunlar, ko‘p tabassumlar va hech qanday bug‘lanmagan plovlar tilayman! 😂

Do‘stingdan: Doniyorbek 😎
"""








# Har bir do'stga xat yozadigan kod

import random

ism = input("Do‘stingizning ismini kiriting: ")

gaplar = [
    "Bugun osmonda quyosh emas, sen porlayapsan!",
    "Sen eng zo‘r do‘stsan – WiFi'dek kerakli! 😄",
    "Hayoting doimo 🍕 va kulgu bilan to‘lsin!",
    "Har doim pozitiv bo‘l, lekin elektr bo‘lma – urib yuboradi!",
    "Hayotingga ‘update’ kerak bo‘lsa, do‘stlaringni yangilama, meni o‘chirib tashlama :)"
]

xat = f"""
Hey {ism}!

Salom, men senga bitta ijobiy energiya to‘la xat yozmoqchiman. 😁

{random.choice(gaplar)}

Do‘sting: Doniyorbek ❤️
"""

print(xat)
