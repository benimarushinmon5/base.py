nombre = input("Entrez le nombre : ")
base_enter = int(input("Base d'entrée : "))
base_exit = int(input("Base de sortie : "))

decimal = int(nombre, base_enter)

if base_exit == 2:
    result= bin(decimal)[2:]
elif base_exit == 8:
    result = oct(decimal)[2:]
elif base_exit == 10:
    result = str(decimal)
elif base_exit == 16:
    result = hexa(decimal)[2:]
else:

    numbers = "0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    result = ""
    while decimal > 0:
        result = numbers[decimal % base_sortie] + resultat
        decimal //= base_sortie

print("Résultat :", result)

