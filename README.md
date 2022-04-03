# Calculadora-de-dobro-triplo-e-raiz-quadrada
Algoritmo que ler um número e mostra o seu dobro, triplo e raiz quadrada
'''
Algoritmo que ler um número e mostra o seu dobro, triplo e raiz quadrada
'''

número = int(input('Digite um número: '))
dobro = número  * 2
triplo = número * 3
raizQuadrada = número**(1/2) # A raiz quadrada de um número é represetada por dos asteriscos juntos.

print(f'O dobro de {número} vale {dobro}.')
print(f'O triplo de {número} vale {triplo}.')
print(f'A raiz quadrada de {número} vale {raizQuadrada:.2f}.')
