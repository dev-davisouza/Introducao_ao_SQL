 Inicialmente, saudações! Sou eu denovo, Davi Souza, atualmente estudando SQL, sei que pode parecer óbvio, mas acho importante deixar claro 
 que eu estou me especializando no Back-end. Enfim, comecemos!
 
nota: Uso o SQlite para trabalhar com SQL(muito prático e leve!).

- Começarei importando o arquivo rexon_metals.db (disponível em: https://github.com/thomasnield/oreilly_getting_started_with_sql). Já inicio consultando a
tabela "CUSTOMER", para isto eu uso a seguinte instrução:

> **SELECT** * **FROM** CUSTOMER; 

- A instrução **SELECT** é usada para fazer uma consulta em SQL, o caractere '*' significa que tudo será selecionado, a instrução **FROM** funciona como
operador de referência à uma tabela, 'CUSTOMER' por sua vez é o nome da tabela (que está sendo referenciada neste caso). o ponto e vírgula é usado justamente para? Pasmem, é pra indicar o fim de uma instrução, neste caso por ser uma instrução única não se faz necessessário o uso dele, porém é provável que futuramente você vai fazer consultas mais complexas e detalhadas, onde até vai ser necessário quebrar em duas ou mais instruções diferentes, pra não esquecer é sempre bom colocar.

nota: Por convenção, toda instrução SQL deve ser digitado em maiúsculo.

- Expressões usando **SELECT**:

> **SELECT** PRODUCT_ID, DESCRIPTION, PRICE, PRICE * 1.07 **AS** TAXED_PRICE **FROM** PRODUCT;

- Aqui, após usar a 1° expressão SQL citada neste documento, conseguimos vizualizar todas as colunas da nossa tabela, depois disso, fazemos uma seleção de cada coluna que queremos vilualizar
