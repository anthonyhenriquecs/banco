import sys
t = int(input("Informe uma opção: \n[1]Sacar \n[2] Extrato:"))
if t == 1:
    valor = float(input("Informe a quantia para o saque: "))
elif t == 2:
    print("Exibindo o extrato")
else:
    sys.exit("Opção invalida")
