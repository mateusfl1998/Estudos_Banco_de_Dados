# ELEVANDO O NIVEL

## Formas de Adicionar Livro ao Banco de Dados:

**OMITINDO COLUNAS**

https://prnt.sc/17dgRvkPfxyB

**COLOCANDO AS COLUNAS**

https://prnt.sc/ZLzCBTP7WMLN

Outro detalhe importante é que o campo Int(de numeros inteiros) tem um range! Você não pode colocar números inteiros menores que -2,147,483,647 e nem maioires que 2,147,483,647; 

**Então se você for criar por exemplo um campo CPF, por exemplo, você deve usar o VARCHAR e não o INT**

## Conhecendo as Projeções - COMANDO SELECT

Select existe em qualquer banco de dados! 

**PROJEÇÃO E JUNÇÃO**

Obrservação: somente o Mysql possuí o comando SHOW TABLES, os outros é necessário usar SELECT 

Você usa colunas para projetar dados que existem e dados que não existem!

**ATENÇÃO**: O COMANDO SELECT NÃO É SELECIONAR, É PROJETAR. O COMANDO DE SELECIONAR É OUTRO

SELECT * FROM CLIENTES não é uma boa prática porque eu esotu trazendo
informações que eu não vou usar. Se num documento eu quero apenas o NOME,SEXO E AMAIL. Se eu der um SELECT * eu trago coisas desnecessárias que vão acabar pesando o banco de dados. Sendo assim, pesa a rede e dificulta para os usuários!

* O profissional de tuning, ele é responsável por olhar as tabelas e fazer otimizações. Ele faz isso através do indice!

Por exemplo eu QUERO buscar um nome: Posso dividir o banco de dados assim:

assim:

*  A À J caminho 1
*  K À Z caminho 2 

assim eu diminuo a minha procura em 50%! essas são formas de otimizar um banco de dados! Se eu usar o * ele vai fazer um full scan  

# SELEÇÕES


projeção usa-se select

para filtrar usa-se where


SELECT NOME, ENDERECO FROM CLIENTE WHERE SEXO = 'F';

FILTRO EM TEMPO REAL! SE CHAMA AJAX O NOME DESSA TECNOLOGIA