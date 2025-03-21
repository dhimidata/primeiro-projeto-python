# primeiro-projeto-python
Primeiro projeto em Python, explorando estruturas de dados básicos
#Listas de frutas
frutas = ["maçã" , "banana" , "laranja" , "uva" ]
#Exibindo as frutas
print("Lista de Frutas")
for fruta in frutas
print (f" - {fruta}")
#Dicionaário de preços
precos = {"maça":3.5, "banana":2.0 , "laranja":4.0, "uva": 6.0}
#Perguntando ao usuário
print("\nQual fruta você gostaria de saber o preço?")
fruta_escolhida = input("Digite o nome da fruta").lower()
#Verificando se a fruta está disponível
if fruta_escolhida in precos:
print(f"O preço de {fruta_escolhida} é R${precos[fruta_escolhida]:.2f}"
else:
print("Desculpa, não temos essa fruta no momento")
