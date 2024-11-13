try:
    a = int(input("sayi 1 gir: "))
    b = int(input("sayi 2 gir: "))
    print(a / b)
    print("işlem burada")
    
except ValueError: 
    print("Lütfen sayı girin")
except ZeroDivisionError:
    print("Bir sayıyı 0'a bölemezsiniz")
finally: # her kosulda calisir 
    print("Burası çalıştı")
print("Blok sona erdi")
