# Primeiros-codigos-em-Python


# Troca de valores 

a = input("Digite o valor de a: ")
b = input("Digite o valor de b: ")
a, b = b, a

print("a =", a)
print("b =", b)


# Calculo da Area 

raio=float(input("Digite o valor do raio: "))
pi=3.14
area=pi*raio**2

print(f"A área do círculo com raio {raio} é {area}.")

# Celsius para fahrenheit

celsius=10
fahrenheit=(celsius*9/5)+32

print(f"{celsius}°C equivale a {fahrenheit}°F.")

# Calculo de IMC

peso=70
altura=1.70
imc = peso / (altura ** 2)

print(f"O IMC para peso {peso} kg e altura {altura} m é {imc:.2f}.")

