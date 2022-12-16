## Entidade

**Entidade pode ser física ou abstrata**

* Algo de importância para um usuário ou
organização que precisa ser representado
em um banco de dados.
* Representa um tema, tópico ou conceito de
negócio.
* Cada objeto de uma entidade é
denominado de **Instância de Entidade**.
* Uma entidade pode ter existência física ou
abstrata.

Ex:Empregados,Livros,Vendas,Produtos. 

* Nomeamos as entidades usando
substantivos que representam de
forma clara e objetiva sua função.
* Por exemplo, podemos ter em um
sistema as entidades Produto,
Cliente, Venda, Estoque,
Catálogo, entre outras.
**colocamos o nome da entidade no singular e dentro de retângulos**


### Algumas regras de nomeação:

Nomes de Entidades:
* Devem começar com uma letra;
* Usar palavra no singular;
* Não podem ter espaços ou alguns
caracteres especiais;
* Alguns caracteres como "$","#"e"_" são
permitidos em alguns bancos de dados.

* Os nomes de colunas devem ser únicos
dentro de uma tabela.

* Os nomes de entidades / tabelas devem se
únicos dentro do esquema(**Esquema é a estrutura dentro de um banco de dados como um todo**).

## Instância de Entidade

Uma entidade em si é uma descrição da estrutura e formato das
ocorrências da entidade, como uma "receita", ou “planta”.
Uma instância de entidade é uma ocorrência específica de uma
entidade.

 **Um produto**

Tabela (Classe de) Entidade.

|Carro|
|-----|
|Fabricante|
|**Modelo**|
|Cor|
|Placa|

|
|
|
V


|Ford|      |Citroen|
|----|      |-------|
|Fiesta|    |C3|
|Azul|       |Vermelho|
|AXJ-4010|    |BUZ-3667|


Tabelas Ford e Citroen São Instâncias de Entidades.