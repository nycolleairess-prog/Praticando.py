# Praticando.py print("conversor de moedas")
print("1 - real para dolar")
print("2 - real para euro")
print("3 - dolar para real")
 
opcao = input("escolha: ")
 
if opcao == "1":
    valor = float(input("valor em reais: "))
    resultado = valor / 5.25
    print("em dolar:", resultado)
 
elif opcao == "2":
    valor = float(input("valor em reais: "))
    resultado = valor / 5.70
    print("em euro:", resultado)
 
elif opcao == "3":
    valor = float(input("valor em dolar: "))
    resultado = valor * 5.25
    print("em reais:", resultado)
 
else:
    print("opcao invalida")
