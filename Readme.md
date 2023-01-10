# Dados X Informação  

Dados sao fatos em uma forma primária que podem ser armazenados em algum meio.

Ex: CPF, Nome, Data 

**um dado sozinho não tem significado, mas dados juntos dão origem a informação:**


**Informação**:São os fatos organizados de maneira a produzir um significado -> dados colocados em contexto . EX : Lista de clientes com seus números de cpf ordenados. 

**Banco de dados organiza dados para poder extrair anotações.**

## Banco de Dados

Banco de Dados (BD) é uma coleção
Organizada de dados. Esses dados são
organizados de modo a modelar aspectos do
mundo real, para que seja possível efetuar
processamento que gere informações relevantes
para os usuários a partir desses dados.
Um BD é composto por diversos objetos, tais
como: tabelas, esquemas, visões, consultas,
relatórios, procedimentos, triggers, entre outros.

**Banco de dados : Tem o simbolo de cilindro pois significa armazenamento**

**Banco de dados é uma coleção(conjunto)  organizados de dados. São modelados para armazenar informações do mundo real. Ex: agenda de amigos.** 

## Aplicações dos Bancos de Dados

Bancos de dados encontram aplicações em
inúmeras áreas, como:
* Sistemas bancários
* Reservas em hotéis
* Controle de estoque em supermercados
* Catálogo de livros em bibliotecas
E-commerce
* Receita Federal
* YouTube

Metadados:
* são dados sobre dados 
* Permite efetuar a representação e identificação dos dados, garantindo sua consistência e persistência (para que sejam sólidos e dados não se percam).
* Os metadados sao mantidos no dicionário de dados (ou em um catálogo de dados).
 

Vai ter tabelas, visões e procedimentos organizados . 


## Banco de dados : Tem o símbolo de cilindro pois significa armazenamento

 SGBD ( sistema de gerenciamento de banco de dados) : CONJUNTO DE SOFTWARE que permite criar ou alterar banco de dados.

 permite também sistema para proteção desse dados.

Exemplos de SGBDs :
• Oracle Database
• Microsoft SQL Server
• MySQL
• IBM DB2
• SAP Sybase
• MongoDB
• Teradata
• PostgreSQL
* SQLite

 SGBDR (R SIGNIFICA RELACIONAL) 


 ## Sistema de banco do dados : 

 contem o  ususário+sgbd(manipulaçao/consultas/definiçaõ)+ banco + aplicativos de acesso 

 Usuário de banco de dados:

 * Administrador (DBA)
 * Projetista/ desenvolvedor
 * Usuário final  - PESSOA QUE UTILIZA

 ### Característica e funcionalidade 

 * controle de redundância : evitar duplicidade dos dados
 * mulltiplas visões de dados : exibir informações de formas distintas 
 * fazer controle de concorrência : Evitar que duas pessoas que estão acessando os dados interfira na ação da outra 
 * Backup e restauração 
 * Autenticação e autorização de acesso 
 * Restrições e Integridade 

 ## Modelagem de banco de dados: 

 **Antigamente os dados era armazenados em fichas**


    Com computador: 

 ### Modelo Hierárquico:

Neste modelo os dados são organizados de
forma hierárquica, com conjuntos de tipos de
registros interconectados por meio de
ligações.
• Uma ligação representa uma relação entre
dois tipos de registros: pai e filho.
Um esquema no modelo hierárquico é um
diagrama de estrutura em árvore.
O acesso aos dados é sempre unidirecional, a
partir do pai ao filho.
  **registro pai e registro filho . Era um diagrama** : 

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

**Para acessar paula : acessa departamento financeiro - paula**


## Modelo em Rede

• No modelo em Redes os dados são
organizados em tipos e ligações
entre dois registros.
Não há restrição hierárquica.
• Tanto o esquema quanto
ocorrências de dados são
visualizados como um grafo
direcionado.


## Modelo Relacional

Neste modelo os dados são separados em
entidades, conforme cada assunto, e
registrados como atributos dessas
entidades.
As entidades se relacionam entre si e
permitem que os dados sejam
armazenados e recuperados de forma
rápida e segura.

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

**Modelo utilizado atualmente !**

Outros temas em ordem : 





