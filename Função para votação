def voto(a,b):
    s = a - b
    return s


#Programa Principal
from datetime import date

atual = date.today().year
print('-' * 25)
ano=int(input('Em que ano você nasceu?'))
r1= voto(atual,ano)
if r1 < 16:
    print(f'Com {r1} anos: NÃO VOTA.')
elif r1 >= 16 and r1 < 18:
    print(f'Com {r1} anos: VOTO OPCIONAL.')
elif r1 >= 18 and r1 < 65:
    print(f'Com {r1} anos: VOTO OBRIGATÓRIO.')
elif r1 >= 65:
    print(f'Com {r1} anos: VOTO OPCIONAL.')
