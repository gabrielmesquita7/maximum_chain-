<h1 align="center">Maximum chain</h1>

<p align="center">
  <a href="#problema">Problema</a> -
  <a href="#desenvolvimento">Desenvolvimento</a> -
  <a href="#entrada">Entrada</a> -
  <a href="#saida">Saida</a> -
  <a href="#executar">Executar</a>
</p>
 

# Problema
### Elabore um programa que receba uma cadeias de DNA. Cada posição da cadeia deve conter um códon, ou seja, uma triade de nucleotídeos → T, A, G, C. Feito isso, leia de um arquivo uma sequência de nucleotídios (i.e., ACGTGGCTCTCTAACGTACGTACGTACGGGGTTATATTCGAT) e tente identificar a maior cadeia da lista que se relaciona a essa entrada.

# Desenvolvimento
### O problema foi desenvolvido da seguinte maneira:

* É definido pelo usuario o tamanho da fila de acordo com o numero de códons, atribuindo o valor para **N** na função **define**
* Também é definido um máximo de 1024 caracteres em uma linha
* Depois é executado a função **MaximaCadeia()**, onde será feita a abertura do arquivo contendo a sequencia de DNA e a entrada do usuario, depois é feito a tokenização do arquivo armazenando a primeira linha na fila e a segunda em um vetor de string. Com isso é printado tanto o segmento de DNA como a entrada e depois se compara os códons da entrada com os do DNA, assim obtendo a maior cadeia entre os códons da entrada
* Por fim é feito a impressão da cadeia obtida
# Entrada
### A entrada do usuário é feito no arquivo _nucleotide_sequence.txt_ e segue a seguinte estrutura:
Linha   | variavel
--------- | ------
1 | DNA
2 | INPUT

# Saida
### É esperado que a saida tenha o print do input do usuario, depois a lista com o segmento de DNA e por fim o print da cadeia obtida. 


# Executar
* Como executar:

```
  make clean
  make
  make run
```
