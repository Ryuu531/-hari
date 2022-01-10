# -hari
Python

print("SEKARANG JAM BERAPA?")
print("Contoh : 16.33 ")

Data = float(input(": "))

Pagi = 6.00
Siang = 12.00
Sore = 15.00
Malam = 18.00

if Data < Pagi :
    print(Data, "jam", Data,"Gelap masih jam tidur")

elif Data < Siang :
    print(Data, "Pagi")

elif Data < Sore :
    print(Data, "Siang")

elif Data < Malam :
    print(Data, "Sore")

else :
    print(Data, "Malam")
