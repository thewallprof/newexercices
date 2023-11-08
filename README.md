# newexercices

Exercícios Iniciais Javascript

Atenção: Essa tarefa pode ser realizada em dupla. Apenas um dos alunos
precisa realizar o fork do projeto. É necessário que esse/a aluno/a adicione o/a colega ao repositório por meio do botão Settings do próprio gitlab.

Responda os exercícios a seguir. Cada exercício deve ser resolvido em um dos
arquivos do diretório js. Por exemplo, o exercício 1 deve ser respondido
no arquivo js/ex1.js. Utilize o arquivo index.html para testar seus scripts
(lembre-se de alterar a tag <script> para carregar os arquivos de cada exercício).


Exercício 1

Escreva um loop que realiza 7 chamadas do comando console.log e exibe o seguinte
"triângulo":

#
##
###
####
#####
######
#######

Talvez seja interessante saber que é possível descobrir o tamanha de uma string
por meio do método .length:

var abc = "abc";
console.log(abc.length);
// → 3

Exercício 2

Escreva um programa que cria uma string que representa um quadro 8x8, utilizando
o caractere de nova linha "\n" para separar cada uma das linhas. Por exemplo:
"linha1..\nlinha2..". Cada posição do quadro deve ser representada por um espaço
em branco (" ") ou um "#". Os caracteres devem produzir a forma de um tabuleiro
de xadrez.

Ao passar a string produzida ao comando console.log, o programa deve exibir
algo parecido com o seguinte:

 # # # #
# # # #
 # # # #
# # # #
 # # # #
# # # #
 # # # #
# # # #
Quando você concluir o exercício acima, altere seu código para que o tamanho
do tabuleiro (8x8, 9x9, ...) possa ser facilmente alterado. Por exemplo, por meio
de uma variável tamanho.
