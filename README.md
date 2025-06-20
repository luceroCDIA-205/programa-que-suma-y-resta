# programa-que-suma-y-resta}
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def main():
    print("Calculadora de suma y resta")
    num1 = float(input("Ingrese el primer número: "))
    num2 = float(input("Ingrese el segundo número: "))
    operacion = input("¿Desea sumar o restar? (escriba 'sumar' o 'restar'): ").strip().lower()

    if operacion == "sumar":
        resultado = suma(num1, num2)
        print(f"El resultado de la suma es: {resultado}")
    elif operacion == "restar":
        resultado = resta(num1, num2)
        print(f"El resultado de la resta es: {resultado}")
    else:
        print("Operación no válida. Por favor, escriba 'sumar' o 'restar'.")

if __name__ == "__main__":
    main()
