# Trabalho da disciplina Linguagens Formais e Autômatos (MATA50) -2018.2

## Trabalho Desenvolvido por Danilo de Andrade Peleteiro e Dimitri Marinho

Especificação:
https://www.moodle.ufba.br/pluginfile.php/622749/mod_resource/content/1/T12018-2.pdf

Data de entrega – 30/09/2018 – depositar no Moodle com o nome dos alunos – grupo de 2 alunos.

1) Estudar as máquinas de Mealy e Moore e a equivalência entre elas. 
Referência: Livro do Hopcroft ou do Blauth tem o assunto.

2) Falar sobre aplicações das máquinas de Mealy e Moore.

3) Construa máquinas de Mealy para a questao (b) e de Moore para a questão (a):

a) Máquina de atraso de 2 unidades. A máquina recebe uma sequência formada por cadeias de 0’s e 1’s e emite a mesma saída com 2
unidades de atraso. Para os dois primeiros instantes de tempo emita uma sequência de dois 0’s.

Ex. entrada = 1011 saída = 001011
entrada = 010 saída = 00010

b) Considere o brinquedo da figura abaixo. Uma gude é jogada na entrada A ou na entrada B. Chaves x1, x2, x3 causam a gude cair à esquerda ou à direita. Quando a gude encontra uma chave, ela causa a chave mudar de estado, de forma que a próxima gude encontre a chave na posição oposta. Denote uma gude jogada em A por entrada 0 e em B por entrada 1. A saída da máquina é a sequência  de C’s e D’s que representam as saídas sucessivas por onde a gude sai.
