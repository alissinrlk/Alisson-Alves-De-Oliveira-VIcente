# Alisson-Alves-De-Oliveira-VIcente
Progama com linguagem em pyton
Explicação: Foi criado tress variaveis (n1),(n2),(s). 
Variavel (n1): comando solicita ao usuário que insira seu nome.
Variavel (n2): Aqui, o programa pede ao usuário que insira sua idade. 
Variavel (S): Este comando calcula quantos anos faltam para que o usuário complete 100 anos, subtraindo a idade atual do usuário (`n2`) de 100.
A mensagem 'Olá, {}!,Faltam {} anos para completar 100 anos' é formatada com os valores de n1 e s usando o método format().
Se o usuário digitar "Maria" como nome e "25" como idade, a saída será: 755


Comandos ultilizados :
n1 = input('Qual e o seu nome?')
n2 = int(input('Qual e a sua idade:'))
s = 100 - n2
print('Olá, {}!,Faltam {} anos para completar 100 anos'.format(n1,s))
