#Calculadora de Média ponderada de notas
num = int(input("Digite a quantidade de números: \n"))
somaNum = 0

for c in range (1, num+1):
    nota = float(input("Informe o valor da {}º nota: \n" .format(c)))
    peso = int(input("Informe o peso da {}º nota: \n".format(c)))
    somaNum += peso
    convert = nota*peso / 100
    somaNum += convert

mediaI = (somaNum / num)
print("-"*30)
print ("A média é de: %.2f"% (mediaI))
