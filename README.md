<h1 align="center">Maximum chain</h1>

<p align="center">
  <a href="#problema">Problema</a> -
  <a href="#desenvolvimento">Desenvolvimento</a> -
  <a href="#saida">Saida</a> -
  <a href="#executar">Executar</a>
</p>
 

# Problema
### Crie uma lista linear que consiga armazenar um conjunto de 100 nomes quaisquer, os quais serão salvos de forma aleatória. Feito a estrutura crie as seguintes ações:

+ Uma função que consiga identificar replicações na lista, ou seja, nomes iguais. Remova todas as réplicas sem mover os ”ponteiro“.
+ Como você gerenciaria os espaços em branco para novas inserções? Qual seria o custo dessas novas inserções?
**R:** Feito a remoção dos mesmos nomes, todo espaço vazio recebe um booleano com o valor true,dizendo que aquele espaço pode ser feito uma nova insercao.

# Desenvolvimento
O problema foi desenvolvido da seguinte maneira:

* É definido o tamanho da fila para 100, ou seja atribuindo o valor 100 para **N** na função **define** de acordo com o problema proposto.
* Logo depois é criado um vetor de strings para armazenar os nomes que serão inseridos randomicamente na fila
* É feito a inserção de valores na fila por meio da função **rand()**
* Depois é executado a função **RemoveSameNames()**, onde será feita as comparações utilizando um ponteiro pra armazenar a variavel do vetor na posição **i** e comparando com todas as outras posições do vetor, assim removendo os nomes iguais e utilizando um booleano para identificar as posições onde pode haver novas inserções
* Por fim é feito a impressão da fila após a remoção dos nomes iguais

# Saida
### É esperado que a saida tenha o print da lista depois de inserido os nomes randomicamente e por fim o print da lista após os nomes iguais serem alterados para **R**, alegando que aquela posição pode haver uma reinserção.


# Executar
* Como executar:

```
  make
  make run
```
