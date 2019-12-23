# Fibonacci
Code to calculate the Fibonacci number

Def fibonacci(n):
	a = 0
	b = 1

	for k in range(n):
		c = a + b
		a = b
		b = c
	return b

n = int(input("Ingrese el valor n: "))
x = fibonacci(n)
print(f"El item en la posición {n} de la serie de Fibonacci es {x}")
