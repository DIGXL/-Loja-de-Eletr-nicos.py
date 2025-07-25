frutas = ["maça", "banana","laranja","uva"]
for fruta in frutas:
    print (frutas)
    
for indice, fruta in enumerate (frutas):
    print (f"indice{indice} : {frutas}")
    
matriz = [[1,2,3], [4,5,6], [7,8,9]]
print (matriz [1][2])


quadrados = [x**2 for x in range (11)]
print(quadrados)


tupla_numeros = (10, 20, 30, 40, 50)
print(tupla_numeros[1:4])
