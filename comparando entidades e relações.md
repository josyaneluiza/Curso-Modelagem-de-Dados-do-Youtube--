# Entidade x Relação

* Uma Entidade é um conceito do mundo real
como por exemplo um Cliente ou um Produ
* Uma Relação é um **conjunto de registros**
(tuplas) que representam um modelo de um
entidade.
* Cada registro representa uma instância de
entidade, e o conjunto de todas as
instâncias, com seus atributos, é chamado
de Relação.


## Relação
Tabela bidimensional com características
específicas, composta por linhas e colunas, criada
a partir de uma entidade.
Características de uma relação:
- Linhas contém dados sobre instâncias de uma
entidade (registros)
- Colunas contém dados sobre atributos da
entidade (campos)


## Relação - características - cont.

* Cada célula da tabela armazena
um único valor
* Todos os valores em uma coluna
são do mesmo tipo (domínio)
* Cada coluna possui um nome
único (não pode ter repetição)
* Não há duas linhas idênticas.
* As relações geralmente geram
tabelas no banco.

## Exemplo de uma Relação 

**Produto**

|ID_Produto|Nome_Produto|Preco_Produto|
|---------|-------------|-----------|
|1000|Mouse|15,00|
|1001|Teclado|20,00|
|1002|WebCam|65,00|


"Toda relação é uma tabela, mas nem toda tabela é uma relação"   


### Relação-Exemplo completo 


Entidade/Tabela : **Produto**

|Cod|Mercadoria|Qtde_Estoque|Fornecedor|Validade|
|----|-------|-------|-------|------|
|189|Azeitonas Pretas| 50 | 05| 02/08/2017|
|222|Peixe Congelado|26| 08| 22/06/2016|
|236|Enlatado|48|  |  |


Cod e seus respectivos números : 
|Cod|
|----|
|189|
|22|
|236|


 São **Chaves Primárias** 

Linhas: 189\Azeitonas Pretas\50\05\02/08/2017\ 

ETC ...

Colunas : |Mercadoria|
          |---------|
          |Azeitonas Pretas|
          |Peixe congelado|
          |Enlatado|


          ETC...



