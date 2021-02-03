# saints
Saints' repository
import random
# Caracteres usados para formar senhas
low = 'abcdefghijklmnopqrstuvwxyz'
up = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
num = '1234567890'
simb = '@#$%&*=-/+.'
# Agrupando todos os caracteres
all = low + up + num + simb
# Definindo o tamanho da senha
length = 10
# Gerando a senha
password = "".join(random.sample(all, length))
# Mstrando o resultado
print('Sua nova senha é {}'.format(password))
