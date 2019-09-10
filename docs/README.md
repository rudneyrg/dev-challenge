# Documentação
Para esse desafio o desenvolvedor deve ler um arquivo `csv` separado por pipe `"|"`, fazer o parse e armazenar na base de dados devidamente normalizada.

## Estrutura do arquivo
O arquivo é composto de registros que contém informações fictícias de uma empresa, fornecedor, notas fiscais e itens.

### Registro 0000
Esse registro contém as informações básicas como por exemplo: nome da empresa

||Campo|Valor|Tipo|
|---|---|---|---|
|1|REGISTRO|0000|String|
|2|DATA INICIAL|01122019|Date|
|3|DATA FINAL|31122019|Date|
|4|NOME|ACME CORPORATION LT|String|
|5|CNPJ|37400218000108|String|


### Registro 0150
Esse registro contém as informações de forncedores

||Campo|Valor|Tipo|
|---|---|---|---|
|1|REG|0150|String|
|2|CODIGO DO PARTICIPANTE|01026018000199|String|
|3|NOME|SPACELY SPACE SPROCKETS|String|
|4|CODIGO DO PAIS|1058|Integer|
|5|CNPJ|01026018000199|String|


### Registro C100
Esse registro contém as informações de notas fiscais emitidas

||Campo|Valor|Tipo|
|---|---|---|---|
|1|REGISTRO|C100|String|
|2|CODIGO DO PARTICIPANTE|01026018000199|String|
|3|CODIGO MODELO|55|String|
|4|CODIGO SITUACAO|00|String|
|5|SERIE|4|String|
|6|NUMERO DO DOCUMENTO|72205|Integer|
|7|CHAVE_NFE|35141201026018000199550040000722051150834390|String|
|8|DATA DO DOCUMENTO|05122019|Date|
|9|DATA DE ENTRADA E SAIDA|05122019|Date|
|10|VALOR DOCUMENTO|10650,53|Decimal|


### Registro C170
Esse registro contém as informações dos itens da notas fiscais

||Campo|Valor|Tipo|
|---|---|---|---|
|1|REGISTRO|C170|String|
|2|NUMERO DO ITEM|1|Integer|
|3|CODIGO DO ITEM|C7|String|
|4|DESCRICAO|DUCATI SCRAMBLER S 500|String|
|5|QUANTIDADE|5000|Decimal|
|6|UNIDADE|UN|String|
|7|VALOR DO ITEM|10650,53|Decimal|
