print (40 * "=")
print ("Calculadora do Amor")
print (40 * "=")

print("Digite o nome da pessoa 1:")
nome1 = input()
print("Digite o nome da pessoa 2:")
nome2 = input()
print(f"Olá, {nome1} e {nome2}! Vamos descobrir se vocês são compatíveis.")
print("Calculando a compatibilidade...")
import random
compatibilidade = random.randint(0, 100)
print(f"A compatibilidade entre {nome1} e {nome2} é de {compatibilidade}%!")
if compatibilidade > 80:
    print("Parabéns! Vocês são um casal perfeito!")
elif compatibilidade > 50:
    print("Vocês têm uma boa compatibilidade, mas ainda podem melhorar.")
else:
    print("Parece que vocês não são tão compatíveis, mas o amor é imprevisível!")
