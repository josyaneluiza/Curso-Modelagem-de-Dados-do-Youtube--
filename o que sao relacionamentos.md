# Relacionamentos

• As Entidades podem ser conectadas
entre si por meio de Relacionamentos.
Trata-se de uma estrutura que indica a
associação de elementos de uma ou mais
entidades


## Porque precisamos de relacionamentos?

Como os dados de diferentes entidades são
armazenados em tabelas distintas, geralmente
precisamos combinar duas ou mais tabelas para
responder às perguntas específicas dos usuários.
Por exemplo, podemos querer saber quais
produtos, e em qual quantidade, foram adquiridos
por um cliente em particular. Precisaremos então
de dados das tabelas de clientes, de pedidos e
produtos para obter essa informação.



## Representando relacionamentos
• Representamos um Relacionamento em
um DER por meio de um Losango que
conecta uma ou mais Entidades:


colocar ligação aqui :



 
 ## Grau de um Relacionamento

O grau de um relacionamento define o
número de entidades que participam do
relacionamento. Assim, um
relacionamento pode ser:
* Unário - grau 1
* Binário - grau 2
* Ternário - grau 3

e assim sucessivamente ....

Os relacionamentos mais comuns são os graus dois  (binário)


### Relacionamento Unário (Recursivo)

Pessoa ------ Se Casa 


Geralmente o nome do relacionamento é um verbo ! 

No caso acima , uma pessoa se casa com outra pessoa !!!


### Relacionamento Binário 

Funcionário------Trabalha------Setor

### Relacionamento Ternário

prescreve--- medico
prescreve--- paciente 
prescreve --- medicamento


## Relacionamentos entre Tabelas
Uma tabela é relacionada com outras tabelas. Por
exemplo, um produto é vendido em uma loja.
|Cliente|
|--------|
|*ID_Cliente*|
|Nome Cliente|
|CPF|


|Vendas|
|------|
|ID_Venda|
|**ID_Cliente**|
|ID_Produto|
|Data_Venda|

Acima está mostrado a associação entre chaves

O grau de um Relacionamento indica o número de entidades envolvidas no relacionamento, como por exemplo unario, binário e ternario.


### Efetuando relacionamento entre múltiplas tabelas

* Cada linha de dados em uma tabela deve ser identificada de forma única usando-se uma Chave Primária (identificador exclusivo).
* Usamos uma Chave Estrangeira para
relacionar os dados entre múltiplas tabelas.
* Usamos para isso o relacionamento entre chave primária de uma tabela com a chave estrangeira em outra tabela.
