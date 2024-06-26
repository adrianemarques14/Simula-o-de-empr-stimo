casa = int(input('Qual o valor da casa?'))
salario = int(input('Qual o seu salário? '))
anos = int(input('Em quantos anos gostaria de pagar? '))
prestacao = (casa/(anos*12))
comparacao = salario * 30 / 100
if prestacao <= comparacao:
    print('O empréstimo pode ser concendido! Sua parcela será de R${:.2f}'.format(prestacao))
else:
    print('Empréstimo reprovado')
