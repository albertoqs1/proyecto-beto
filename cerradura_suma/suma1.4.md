print("cerradura: la suma de dos numeros reales da como resultado otro numero real.")
print("a + b pertenece R")
print() 
num1 = float(input("ingresa num1: "))
num2 = float(input("ingresa num2: "))
#calcular suma
suma = num1 + num2
if suma.is_integer():
    res = "entero"
else:
    res = "racional"
    print("result de la suma",suma)
    print("reslt de num",res)
    