# projetos-em-python
alguns projetos e codigos que podem ser uteis para vocês
para que alguns codigos funcionem tem que importar a biblioteca
(import math)
(import random)

real = float(input("digite o valor em reias: "))
resultado = real / 5.06
print("resultado: {:.2f} ".format(resultado))

print("=" * 20)
largura = float(input("digite a largura(em m): "))
altura = float(input("digite a altura(em m): "))
area = altura * largura
print("a area é de: ",area , "metros")
tinta = area / 2
print("vc precisara de ", tinta , "litros de tinta")

print("=" * 20)
produto = float(input("qual o valor do produto: "))
desconto = produto - (produto * (5/100))
print("seu produto vale: ",produto , "com 5% ele ira valer: ",desconto)

print("=" * 20)
salarioAt = float(input("digite o salario atual: R$ "))
aumento = 15/100
novoSala = salarioAt + (salarioAt * aumento)
print("o novo salario vai ser: R$ ",novoSala)

print("=" * 20)
grausCel = int(input("digite a temperatura em C°: "))
conversao = (grausCel * 9 )/ 5 + 32
print(grausCel, "C° vale ", conversao, "F°")


print("=" * 20)
angulo = int(input("digite um angulo(em °): "))
seno = math.sin(angulo)
coss = math.cos(angulo)
print(angulo,"°", seno, coss)

print("=" * 20)
al1 = input("digite o nome do aluno 1: ")
al2 = input("digite o nome do aluno 2: ")
al3 = input("digite o nome do aluno 3: ")
al4 = input("digite o nome do aluno 4: ")
listaDeAl = [al1, al2, al3, al4]
sorteioAl =random.choice(listaDeAl)
print("o sortudo foi: ", sorteioAl)

print("=" * 20)
numeroAle = random.randint(1, 30)
print(numeroAle)

print("=" * 20)
aluno1 = input("digite o nome do aluno1: ")
aluno2 = input("digite o nome do aluno2: ")
aluno3 = input("digite o nome do aluno3: ")
aluno4 = input("digite o nome do aluno4: ")
listaDosAlu = [aluno1, aluno2, aluno3, aluno4]
random.shuffle(listaDosAlu)
print(listaDosAlu)
