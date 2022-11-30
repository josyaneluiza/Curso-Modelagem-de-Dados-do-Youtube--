Dados X Informação  

Dados sao fatos em uma forma primária que podem ser armazenados em algum meio.

Ex: CPF, Nome, Data 

um dado sozinho não tem significado, mas dados juntos dao origem a informação :


Informação :São os fatos organizados de maneira a produzir um significado -> dados colocados em contexto . EX : Lista de clientes com seus números de cpf ordenados. 

Banco de dados organiza dados para poder extrair anotações.

Metadados:
* sao dados sobre dados 
* Permite efetuar a representação e identificação dos dados, garantindo sua consistencia e persistencia (para que sejam solidos e dados nao se percam).
* Os metadardos sao mantidos no dicionario de dados (ou em um catalogo de dados)


Banco de dados é uma coleçao(conjunto)  organizados de dados. São modelados para armazenar informações do mundo real. Ex: agenda de amigos. 

Vai ter tabelas, visões e procedimentos organizados . 


Banco de dados : Tem o simbolo de cilindro pois significa armazenamento

Pra que serve : 

* criar sistema bancário (açoes, dinheiro)
 *reserva de hotel
 * catalago de livro
 * controle de estoque
 * loja e - commerce 
 * receita federal para dados dos 
 * cidadaos
 youtube
 etc..



 SGBD ( sistema de gerenciamento de banco de dados) : CONJUTNO DE SOFTWARE que permite criar ou alterar banco de dados

 permite tambem sistema para proteçao desse dados 

 ex : SQL 
 ORACLE
 ...



 SGBDR (R SIGNIFICA RELACIONAL) 


 Sistema de banco do dados : 

 contem o  ususário+sgbd(manipulaçao/consultas/definiçaõ)+ banco + aplicativos de acesso 

 Usuário de banco de dados:

 * Administrador (DBA)
 * Projetista/ desenvolvedor
 * Usuário final  - PESSOA QUE UTILIZA

 Caracteristica e funcionalidade 

 * controle de redundancia : evitar duplicidade dos daods
 * mulltiplas visoes de dados : exibir infromaçoes de fromas distintas 
 * fazer controle de concorrrencia : Evitar que duas pessoas que estao acessando os dados interfira na açao da outra 
 * Backup e restauração 
 * Autenticacao e autorizacao de acesso 
 * Restriçoes e Integridade 

 Modelagem de banco de dados : 

 Antigamente os dados era armaznados em fichas 


 com computador : 

 modelo hierarquico : registro paia e regisro filho . Era um diagrama : 

 ```mermaid
graph TD;
    Departamento-->RH;
    Departamento-->Financeiro;
    Departamento-->Engenharia;
    RH-->Ana;
    RH-->Jorge;
    Financeiro-->Paula;
    Financeiro-->Renato;
    Engenharia-->Fábio;
    Engenharia-->Monica;
```

Para acessar paula : acessa departamento finaiceira - paula 


Modelo em rede :




modelo relacional :

* 
* inclusive de



|Aluno|
|-----|
|Ra Int|
|Nome VARCHAR|
|Curso Varchar|  

-->

|Curso|
|-----|
|Cod INT|
|Nome VARCHAR|
|Duracao DATE|

-->

|Professor|
|---------|
|ID INT|
|Nome Varchar|


