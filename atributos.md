# Atributos

Os atributos descrevem características da
entidade, como por exemplo: fabricante, modelo,
cor, placa, etc.
• Os atributos possuem um tipo de dados (domínio)
nome e valor específico.

## Representando Atributos
• Os atributos podem ser representados por uma elipse
contendo o seu nome, ligada à entidade que qualifica
• Opcionalmente, podemos representar um atributo
apenas pelo seu nome ligado à entidade, sem utilizar a
elipse.


Departamento --------(Função) 

o parênteses acima representa a elipse como semi-cículo.


Departamento----------Função



# Tipos de Atributos
Os atributos podem ser de vários tipos, tais como:

• Simples
• Composto
• Multivalorado
• Determinante
• Identificador
entre outros.


## Atributo Simples / Atômico

Não possui características especiais, e são
indivisíveis.
Ex.: Nome da empresa, CPF, CNPJ

Empresa --------Nome


## Atributo Composto

É formado por itens menores; pode ser
em outros atributos.
Ex.: Endereço da empresa:

----Empresa--------Endereço-----
-----Rua
----Endereço
-----CEP
----Bairro

## Atributo Multivalorado


Pode conter mais de um valor para um mesmo
registro (informação).
Ex.: Telefone da empresa

Empresa-------*Telefone

Antes de dar um nome a uma atributo multivalorado a gente colocar um asterísco



## Atributo Determinante

Define de forma única as instâncias de uma
entidade.
Não podem existir duas instâncias com o
mesmo valor nesse atributo.
Ex.: CNPJ da empresa, Código de Produto

Empresa-----~~CNPJ~~ geralmente sublinhado quando o atributo for o determinante

## Atributos Identificadores ("Chaves")

Uma chave identifica uma instância específica na classe de entidade.
Ex.: CPF, CódigoProduto, Matrícula, ID_Setor 

As chaves podem ser únicas ou não-únicas:
- Únicas: O valor dos dados da chave é único na
entidade
- Não-única: Usada para agrupar instâncias de
classe em categorias.

As chaves podem ser compostas, consistindo de dois ou mais atributos combinados.
 
 colocar captura de tela aqui : 

 
 ## Exemplos de Representação de Entidades e Atributos

Podemos também representar uma entidade de forma textual:

Produto(Cod_Produto, Nome_Produto, Preço, Qtde_Estoque)

