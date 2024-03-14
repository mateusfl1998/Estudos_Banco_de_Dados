# Lógica de Predicados

Tabela verdade: https://prnt.sc/QZrnWk5BAVXS

**OR** - PARA A SAÍDA DA QUERY SEJA VERDADEIRA, BASTA APENAS QUE UMA CONDIÇÃO SEJA VERDADEIRA!

**AND**: PARA QUE A SAIDA SEJA VERDADEIRA, TODAS AS CONDIÇÕES PRECISAM SER VERDADEIRAS!

## PERFORMANCE

**Funções de agregações:**

selec count(*) AS from livro;

Uma das maneiras de otimizar a busca no banco de dados com 'OR' é colocando a opção
que tem mais probabilidade de acontecer na frente! 

**Para otimizar as buscas com AND:** você deve colocar primeiro o dado que tem menos possibilidade de aparecer e o que tem mais em segundo lugar, diferente do 'OR'

Pegou um banco de dados novo para analisar, certifique-se que você não está num horário de pique para realizar suas análises no banco

Para fazer essas analises você desenha duas barras e verifica se vai trabalhar com OR ou AND

* And menor barra na frente
* Or maior barra na frente ! Simplesa assim!