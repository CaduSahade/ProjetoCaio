print(15*'=-')
print('|      -- BEM - VINDO --     |')
print(15*'=-')
print()
print('Selecione a opção : ')
print('[1] - Login')
print('[2] - Cadastrar')
print('[3] - Esqueci a senha')
print()

opcao = int(input()) 


lista_usuario = []
lista_senha = []

if opcao == 1:
  print()
  usuario = str(input('Digite seu nome: '))
  lista_usuario.append(usuario)
  senha = str(input('Digite sua senha:'))
  lista_senha.append(senha)
  print(15*'=-')
  print('- Login feito com sucesso -')
  print(15*'=-')

elif opcao == 2:
  print()
  cadastrar_usuario = str(input('Crie um usuario: '))
  lista_usuario.append(cadastrar_usuario)
  cadastrar_senha = str(input('Crie uma senha: '))
  lista_senha.append(cadastrar_senha)
  print(15*'=-')
  print('-        Conta criada       -')
  print(15*'=-')

elif opcao == 3:
  esqueci_senha = (input('Digite seu e-mail de cadastro: '))
  print('Uma mensagem foi enviada no seu email')

else:
  print('----------------')
  print('|Opção invalida|')
  print('----------------')


with open('usuarios.txt', 'a') as arquivo_usuario:
  i = 0
  while i < len(lista_usuario):
    usuarios = lista_usuario[i]
    senhas = lista_senha[i]
    arquivo_usuario.write(usuarios)
    arquivo_usuario.write(';')
    arquivo_usuario.write(senhas)   
    arquivo_usuario.write('\n')
    i+=1
  
  print('Usuario gravado com sucesso')
