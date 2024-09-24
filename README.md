# Pr-en-clase-promedio-tres-numeros
Alvaro Campechano Estrada 3W

print(" ")
print("Alvaro Campechano practica en clase donde se soliciten tres numeros para luego mostrarle el promedio de los tres")
print(" ")
# Programa para calcular el promedio de tres números

# Función para calcular el promedio
def calcular_promedio(num1, num2, num3):
    return (num1 + num2 + num3) / 3

# Solicitar al usuario que ingrese tres números
try:
    # Ingresar el primer número
    numero1 = float(input("Ingrese el primer número: "))
    
    # Ingresar el segundo número
    numero2 = float(input("Ingrese el segundo número: "))
    
    # Ingresar el tercer número
    numero3 = float(input("Ingrese el tercer número: "))
    
    # Calcular el promedio
    promedio = calcular_promedio(numero1, numero2, numero3)
    
    # Mostrar el resultado
    print(f"El promedio de {numero1}, {numero2} y {numero3} es: {promedio:.2f}")
except ValueError:
    # Manejar el caso en que la entrada no sea un número válido
    print("Por favor, ingrese números válidos.")

![image](https://github.com/user-attachments/assets/da354ee2-00a6-47ff-92ef-d2117edf7ddf)

