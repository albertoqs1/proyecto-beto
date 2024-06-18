num1 = float(input("ingresa num1: "))
num2 = float(input("ingresa num2: "))

if num1 > num2:
    print("el primer num ({}) es mayor que el segundo ({})".format(num1, num2))
elif num1 < num2:
    print("el segundo num ({}) es mayor que el primer ({})".format(num2, num1))
else:
    print("ambos numeros son igiales")
