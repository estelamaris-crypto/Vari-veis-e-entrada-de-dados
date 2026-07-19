# Variveis-e-entrada-de-dados 
# (uma forma de separar alternativa de separar números grandes é utilizar o sublinha entre os dígitos, a partir do Python3.6)
1_000 # Mil
1000
1_000_000 # Um milhão
1000000
1_0_0 # Cem, válido, mas a evitar
100
1_980.10 # _ pode ser combinado com ponto
1980.1
# usar ponto para separar as casas decimais e o sublinha ( opcionalmente ) para  separar os milhares 
# variáveis do tipo lógico ( True - para verdadeiro e False - para falso )
a=1 # a recebe 1
b=5 # b recebe 5
c=2 # c recebe 2
d=1 # d recebe 1
a==b # a é igual a b ?
False
b>a # b é maior que a?
a<b # a é menor que b?
True
a==d # a é igual a d?
True
b>=a # b é maior ou igual a a?
True 
c<=b # c é menos ou igual a b?
True
d!=a # d é diferente de a?
False
d!=b # d é diferente de b?
True
# variáveis de tipo lógico também pode ser utilizado para armazenar o resultado de expressões e comparações 
nota=8
média=7
provado=nota>=média
print(aprovado)
True
# exercício 3.2 ( complete a tabela a seguir, respondendo True ou False. Considere a=4, b=10, c=5.0, d=1 e f=5
a=4
b=10
c=5.0
d=1
f=5
a==c
False
a<b
True
d>b
False
c!=f
False
a==b
False
c<d
False
b>a
True
c>=f
True
f>=c
True
c<=c
True
c<=f
True
# operadores lógicos ( operações logicas booleana, o Python suporta três operadores básicos: not(não) , and(e), or(ou)
# quando o operador utiliza apenas um operando( operador unário ) ao utilizar dois operadores ( operador binário )
# O operador de negação (NOT) é um operador unário e ( ou ) e ( and ) são operadores binários precisando de dois operandos.
# Not é o operador mais simples pois precisa apenas de um operador, chamada também de inversão
not True
False
not False
True
# o operador and resulta verdadeiro apenas quando seus dois operadores forem verdadeiros 
True and True
True
True and False
False
False and True
False
False and False
False
# Excercício 3.3 complete a tabela a seguir utilizando ( a=True, b=False e c=True)
a=True
b=False
c=True
a and a 
True
b and b 
False
not c
False
not b
True
not a 
True
a and b
False
b and c
False
a or c
True
b or c
True
c or a
True
c or b
True
c or c
True
b or b
False
# Excercício 3.4 Escreva uma expressão para determinar se uma pessoa deve ou não pagar imposto. Considere que pagam imposto pessoas cujo salário é maior que R$ 1.200,00.
# já tentei fazer esse crlh e não roda, senhor me ajuda por favor OWO dai me uma luz !
salário=1500.00
resultado=salário>1200.00
print(resultado)
True
# excercício 3.5 calcule o resultado da expressão ( a>b and c or d ) utilizando os valores da tabela a seguir 
# linha 1
A=1
B=2
C= True
D= False
print(A>B and C or D)
True
# linha 2
A=10
B=3
C= False
D= False
print(A>B and C or D)
False
# linha 3
A=5
B=1
C= True
D= True
print(A>B and C or D)
True
# Excercício 3.6 escreva uma expressão que será utilizada para decidir se um aluno foi aprovado ou não aprovado. Para ser aprovado, todas as médias do aluno devem ser maiores ou iguais a 7. Considere que o aluno cursa apenas três matérias, e que a nota de cada uma está armazenada nas seguintes variáveis: matéria1, matéria2 e matéria3.
matéria1= 8.0
matéria2= 7.0
matéria3= 9.0
resultado=(matéria1 >= 7) and (matéria2 >= 7) and (matéria3 >= 7)
print(resultado)
True
# fim
