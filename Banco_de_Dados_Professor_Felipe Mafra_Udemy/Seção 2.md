# Arquitetura de Software

o papel do banco de dados e guardar informações e do front end é exibir as informações na tela!

arquitetura de softaware:

MVC - MODEL - VIEW

https://prnt.sc/qSBDbCsWIbFn

# Modelagem Lógica e Física

Antes de fazer o projeto de banco de dados para uma pessoa, temos que definir o escopo do projeto. Porque as vezes o cliente pode pedir mais coisas e vc tem que tirar tempo e dinheiro do seu bolso. Tem que deixar claro o que vai ser feito! 

Vamos criar uma modelagem somente de clientes para uma empresa:

### 3 FASES DA MODELAGEM DE DADOS

**ADM DE DADOS FAZ O 1 E O 2**  

_1 - MODELAGEM CONCEITURAL:_ Escopo de como vai funcionar o banco de dados! Conversa entre cliente/prestador de serviço. Pode ser feito no excel, world, até mesmo numa folha de papel

_1 - MODELAGEM LOGICA:_
Pega tudo que foi feito na modelagem conceitual e coloca num programa de modelagem de banco de dados. Exemplo BR MODELO 3.0


**TABELA CLIENTE**

*NOME* - CARACTERES (30) 

*CPF* - NUMERICOS (11)

*EMAIL* - CARACTERES (30)

TELEFONE - CAMPO NUMERICO (30)

ENDERECO - CARACTERES   (30)

SEXO - CATACTERE(1)

**Observações**: entidade = tabela! / campos = atributos!

_1 - MODELAGEM FISICA:_
Scripts de Banco de dados e tipagem!

# Modelagem Física
SGBD = SISTEMA DE GERENCIAMENTO DE BANCO DE DADOS!

Quanto maior o banco de dados mais é demorado buscar dados, vc pode ajudar o algoritimo a buscar os dados mais rápidos, um dos métodos é usar VAR e VARCHAR da forma correta, conforme a imagem:

https://prnt.sc/wvSPhS6X7gjc

### Á AREA DE DADOS É BASTANTE EXTENSA, EU TENHO:

* O AD QUE CUIDA DOS DADOS! 
* DBA QUE ESTUDA A ESTRUTURA DO BANCO DE DADOS!
* CARA DE TUNING QUE CUIDA DA PERFORMANCE DO BANCO DE DADOS!
* DS (DATA SCIENCE) PARA VER O QUE PODE OCORRER NO FUTURO
* AREA DE MINERAÇÃO DE DADOS

https://prnt.sc/RXqDna12N1LA

# COMPARANDO CHAR E VACHAR

https://prnt.sc/47kINDtHFo5Y

ANALISTA DE PERFORMANCE : TUNNING
https://prnt.sc/j6FoGNlJbQri

EXEMPLO DE QUAL A DIFERENÇA ENTRE CHAR E VARCHAR: 
https://prnt.sc/aul018M9MnZ3

VARCHAR CORTA, O CHAR NÃO CORTA!

# COMPARANDO NUM E ENUM

ENUM: https://prnt.sc/4Dp-VJ4evBtY