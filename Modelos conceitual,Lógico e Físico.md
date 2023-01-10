# Modelagem de Dados - Níveis
# Classificamos o processo de
# modelagem de dados em três níveis:
• Modelo Conceitual (alto nível) -
MCD
* Modelo Lógico - MLD
• Modelo Físico (baixo nível) - MFD

## Modelo Conceitual :

Esta é a primeira fase da modelagem, onde
representaremos o mundo real por meio de uma visão
simplificada dos dados e seus relacionamentos. Assim
poderemos determinar quais informações serão
armazenadas no BD.
Neste nível o projeto é independente de SGBD
Exemplo:
Cadastro de Produtos em uma Loja
Dados necessários: Nome do produto, categoria de
produto (limpeza, higiene, etc), código do fornecedor,
Slide?

Neste nível, detalhes da implementação não
aparecem, porém é suficientemente
detalhado para a ponto de ser possível
descrever os tipos de dados requeridos, seus
relacionamentos entre si e regras de
consistência.

## Modelo Lógico


 ```mermaid
graph TD;
    Trabalha-->departamento;
    Trabalha-->Funcionário;
    Funcionário-->ID_Setor;
    Funcionário-->Nome;
    Funcionário-->Cargo;
    Departamento-->ID_Setor.;
    Departamento-->Nome;
```

Um modelo lógico possui conceitos que os
usuários são capazes de entender, ao mesmo
tempo em que não está distante do modelo físico
do banco de dados.
Neste nível o projeto é independente de SGBD.
Consiste na especificação lógica dos dados em
um formato adequado ao SGBD escolhido. Os
tipos de dados são completamente definidos.

## Modelo Físico 

|Nome do campo|Tipos de Dados|Tamanho|
|------------|-------|-------|
|ID_Cliente|Inteiro| 4|
|Novo_Cliente|Caracteres|30|
|Endereço|Caracteres|40|


**Exemplo- Estrutura de cadastro de Clientes**


* A partir de um modelo lógico nós derivamos
o modelo físico, onde se detalham os
componentes de estrutura física do banco de
dados, incluindo as tabelas, campos, tipos de
valores, restrições, etc.
* Ao criarmos o modelo físico, poderemos partir
para a implementação física do banco de
dados, utilizando o SGBD mais adequado.


## Arquitetura de Três Níveis 

```mermaid
graph TD;
    Mundo Observado-->Modelo Conceitual;
    Modelo Conceitual-->Modelo Lógico;
    Modelo Lógico-->Modelo Físico;
```

## Esquema do Banco de Dados


* Um Esquema é uma definição do Banco de
Dados especificada durante o projeto,
armazenada no Dicionário de Dados.
* Um Esquema (Schema) raramente muda
durante a vida do BD.
* Trata-se da organização dos dados em um
plano que mostra como o banco é construído.
* O esquema define tabelas, campos,
relacionamentos, visões, funções e muitos
outros elementos que compõem o BD.



## Etapas do desenvolvimento de um BD

**As principais etapas no desenvolvimento de um BD são:**

1. Especificação e Análise de Requisitos
a.Os requisitos são documentados
2. Projeto Conceitual
a. Baseado nos requisitos
3. Projeto Lógico
a. Expresso em um modelo de dados, como o
relacional
4. Projeto Físico
a.Especificações para armazenar e acessar o
banco de dados
b. Implementação do BD, inserção de dados reais
e manutenção.


## Tarefas para Modelagem

As tarefas a seguir devem ser realizadas para que seja
possível efetuar modelagem de dados e projeto de BD
funcional:
Identificar os tipos de entidade
Identificar atributos
Identificar relacionamentos
Criar e associar chaves
Normalizar para reduzir redundância
Desnormalizar para aumentar performance


## MER
Após o levantamento dos requisitos, estes são
transformados em um Modelo
Entidade-Relacionamento (MER), o qual
consiste dos seguintes elementos:
Entidades
Relacionamentos
Atributos
O modelo é posteriormente refinado com o uso
de técnicas específicas, e finalmente
implementado em um banco de dados físico.








