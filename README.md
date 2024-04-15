# binario
exercicio binario
num = int(input("entre um numero: "))
i = 0
saida = 0
var = 1

#num é o numero de entrada que o usuario coloca
#i é um indice para concatenar os binarios obtidos
#saida é a variavel que armazena a soma dos valores obtidos
#var é uma variavel para operar o algoritmo

while var != 0:
	var = num//2
	bin = (num - 2*var)*10**i
	num = var
	i = i+1
	saida = saida + bin
print (saida)
