# Prolog-Study-case

Estudo de caso desenvolvido para apresentação na materia de LP

Prolog é uma linguagem de programação que se enquadra no paradigma de Programação em Lógica Matemática. É uma linguagem de uso geral que é especialmente associada com a inteligência artificial e linguística computacional. Consiste numa linguagem puramente lógica, que pode ser chamada de Prolog puro, e numa linguagem concreta, a qual acrescenta o Prolog puro com componentes extra-lógico.

## 📌Histórico 
A linguagem de programação Prolog nasceu de um projeto que não focava em implementações de linguagens de programação, mas sim em processamento de linguagem natural. Na Universidade de Marselha, Alain Colmerauer e Robert Pasero trabalharam na parte da linguagem natural, e Jean Trudel e Philippe Roussel trabalharam na parte dedutiva do projeto. Trudel, interessado em métodos de resolução de SL, convenceu um de seus inventores, Robert Kowalski, a participar do projeto. O projeto produziu uma versão preliminar da linguagem Prolog no final de 1971, com a versão final aparecendo no final de 1972.

## Características 

O Prolog é uma linguagem declarativa, ou seja, não é especificado passo a passo como em linguagens procedurais ou orientadas a objetos, ele fornece d destinado a usar uma coleção de fatos e regras (lógica) para indicar que o problema proposto deve ser foi resolvido. Como vimos, o Prolog está mais preocupado do que o próprio algoritmo.

Além de ser uma linguagem declarativa, outro fato que a diferencia de outras linguagens é que ela não possui as estruturas de controle (if-else, do-while, for, switch) que existem na maioria das linguagens de programação. Para fazer isso, usamos a lógica para declarar como você deve atingir seus objetivos.

Os programas em Prolog podem ser executados de forma interativa e os usuários podem formular consultas usando fatos e regras, resultando em soluções por meio de um mecanismo unificado.

- ESCOPO<br>

## Tipos de dados 
Os tipos de dados comuns em outras linguagens não são usados no Prolog. Todos os dados são tratados como um único tipo, chamado de termo, que pode ser uma constante, variável ou termo composto.

- FATOS<br>
 Em Prolog são fornecidos os fatos e as regras para uma base de dados, que posteriormente serão executadas consultas (queries) em cima da base de dados.
 
 
A estrutura de um fato é formada por um `predicado`, seus `argumentos` e com um ponto`(.)` para finzalizar a instrução seria como ponto-vírgula das linguagens comuns de programação
```
predicado(argumento1,argumento2...).

Ex: Cidade(Cascavel)
```
- QUESTOES<br>
Questão é um fato antecedido de um ponto de interrogação ou o comando apropriado para o tipo de compilador.<br>

```
Por exemplo: ?-Cidade(cascavel).
```
A partir de uma questão feita o Prolog realiza uma busca procurando por uma ocorrencia que seja igual a questão e retornando assim `YES` ou `NO`

- VARIAVEIS<br>
No Prolog as variareis são tratadas como incógnitas das quais o valor é desconhecido, portando devemos instanciar um objeto a essa variável e a mesma não poderá ser mais modificada

- LISTAS<br>

- ÁTOMOS<br>




