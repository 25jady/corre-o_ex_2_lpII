tipo = input('Tipo do quarto: ')
dias = int(input('Quantidade de diárias: '))
fone = input('Usou Telefone: ')
tv = input('Usou TV: ')

valor_total = 0
if tipo == 'P':
    valor_total = dias * 160
elif tipo == 'S':
    vlor_total = dias * 110
elif tipo == 'C':
    valor_total = dias * 85
else:
    print('Tipo inválido')
    exit()
