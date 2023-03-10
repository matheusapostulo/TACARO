# INTRODUÇÃO

Analisando a sociedade atual, é indubitável que as classes econômicas C e D continuam em uma busca incansável dos melhores preços dos produtos nos supermercados. Atualmente, a dor de um software auxiliar cresce e a busca continua, dor que foi deixada de lado após a extinção dos panfletos promocionais enviados por grandes supermercados para as residências de seus clientes geograficamente posicionados ao redor do estabelecimento. Dessa forma, TACARO vem com a iniciativa de aproximar o usuário, de forma interativa, os preços da sua região na palma da sua mão, visando economicamente a comparação de preços e promovendo ofertas, ajudando o cliente a fazer a melhor escolha de compra.

#### DEFINIÇÃO DE DEMANDA  

1.	PROBLEMA OU OPORTUNIDADE PERCEBIDA  
De acordo com o CNN Brasil, em uma pesquisa realizada em 2022, cresceu gradativamente a procura por produtos “mais baratos” para atender a nova realidade.
“a alta nos preços vem provocando uma mudança nos hábitos dos brasileiros e, consequentemente, readequações nos supermercados.”

2.	RAZÃO/JUSTIFICATIVA PARA ESTA DEMANDA  
Em uma pesquisa realizada por parte do Estudo Varejo Alimentar, da CVA Solutions, clientes de supermercados estão em uma busca incansável por preços reduzidos e promoções.  
Dessa forma, é possível visualizar uma dor em procura por produtos mais baratos, em que o software auxiliaria a procura mais rápida e certeira em qual estabelecimento ele deve realizar a compra para economizar.   
https://www.cnnbrasil.com.br/business/cresce-procura-por-marcas-mais-baratas-nos-supermercados-aponta-abras/       
https://portal.clientesa.com.br/cliente-sa/consumidores-buscam-precos-e-promocoes-para-lidar-com-inflacao-alta/    

3.	DESCRIÇÃO DO SOFTWARE  
TACARO é uma aplicação mobile que tem como objetivo principal escanear códigos de barra e realizar a análise de preços de supermercados da região de acordo com o produto pesquisado, promovendo a ideia de realizar compras econômicas.

4.	IDENTIFICAÇÕES DE CLIENTES  
Os clientes público-alvo da aplicação são pertencentes da classe C e D, entre 18-60 anos de idade, com predominância de compras em alimentos e produtos de limpeza nos grandes supermercados e que buscam realizar compras com preços reduzidos e promoções.

5.	ETAPAS NECESSÁRIAS PARA CONSTRUÇÃO DO PROJETO     
I.	Estudo aprofundado da API e da leitura de código de barras;    
II.	Estudo inteligente de abordagem ao usuário com telas e usabilidade;    
III.	Levantamento de requisitos;    
IV.	Criação de protótipos;      
V.	Início de produções.   

6.	PRINCIPAIS CRITÉRIOS DE QUALIDADE   
I.	Boa usabilidade/fácil manuseio;   
II.	Navegação rápida;   
III.	Informações coerentes de acordo com a localização do usuário.   


# Levantamento de Requisitos
### LEITURA DO CÓDIGO DE BARRAS
|   [RF001]   | LEITURA DO CÓDIGO DE BARRAS |
| --- | --- |
| NÚMERO DO REQUISITO | 1 |
| DESCRIÇÃO | O sistema deve realizar a leitura do código de barras |
| CLASSIFICAÇÃO | Requisito Funcional. |
| DEPENDÊNCIAS | [RF005] * perguntar para o prof se pode ter depedencia de um requisito descristo posteriormente | 
| ESFORÇO (PARA DESENVOLVER) | Alto. |
| RELEVÂNCIA (PARA NEGÓCIO) | Alta. |
| RISCO (PARA O PROJETO) | Alto. |
***  
  
### IDENTIFICAÇÃO GEOGRÁFICA DO USUÁRIO
|   [RF002]   | IDENTIFICAÇÃO GEOGRÁFICA DO USUÁRIO |
| --- | --- |
| NÚMERO DO REQUISITO | 2 |
| DESCRIÇÃO | O sistema deve identificar a localização geográfica do usuário |
| CLASSIFICAÇÃO | Requisito Funcional. |
| DEPENDÊNCIAS | Aceitação de termos; GPS ligado |
| ESFORÇO (PARA DESENVOLVER) | Alto. |
| RELEVÂNCIA (PARA NEGÓCIO) | Alta. |
| RISCO (PARA O PROJETO) | Alto. |
*** 
  
  
### IDENTIFICAÇÃO DO PRODUTO
|   [RF003]   | IDENTIFICAÇÃO DO PRODUTO |
| --- | --- |
| NÚMERO DO REQUISITO | 3 |
| DESCRIÇÃO | O sistema deve ser capaz de identificar o produto com base no código de barras escaneado|
| CLASSIFICAÇÃO | Requisito Funcional. |
| DEPENDÊNCIAS | [RF001] |
| ESFORÇO (PARA DESENVOLVER) | Alto. |
| RELEVÂNCIA (PARA NEGÓCIO) | Alta. |
| RISCO (PARA O PROJETO) | Alto. |
***  
  
### ATUALIZAÇÃO DE PREÇO
|   [RF004]   | ATUALIZAÇÃO DE PREÇO |
| --- | --- |
| NÚMERO DO REQUISITO | 4 |
| DESCRIÇÃO | O sistema deve atualizar o preço de um produto|
| CLASSIFICAÇÃO | Requisito Funcional. |
| DEPENDÊNCIAS | [RF003] |
| ESFORÇO (PARA DESENVOLVER) | Alto. |
| RELEVÂNCIA (PARA NEGÓCIO) | Alta. |
| RISCO (PARA O PROJETO) | Médio. |
***  
  
### ESCANEAMENTO PELO CLIENTE
|   [RF005]   | ESCANEAMENTO PELO CLIENTE |
| --- | --- |
| NÚMERO DO REQUISITO | 5 |
| DESCRIÇÃO | O sistema deverá ter uma tela exibida simples onde o usuário irá clicar em "ESCANEAR" e logo abrirá para a leitura do código de barras [RF001] |
| CLASSIFICAÇÃO | Requisito Funcional. |
| DEPENDÊNCIAS | NENHUMA * cadastro seria uma dependência |
| ESFORÇO (PARA DESENVOLVER) | Alto. |
| RELEVÂNCIA (PARA NEGÓCIO) | Alta. |
| RISCO (PARA O PROJETO) | Alto. |
*** 
  
### VISUALIZAÇÃO DE PREÇO
|   [RF006]   | VISUALIZAÇÃO DE PREÇO |
| --- | --- |
| NÚMERO DO REQUISITO | 6 |
| DESCRIÇÃO | O usuário poderá ver os preços (de outros mercados) do produto escaneado |
| CLASSIFICAÇÃO | Requisito Funcional. |
| DEPENDÊNCIAS | TODAS (RESULTADO FINAL) |
| ESFORÇO (PARA DESENVOLVER) | Alto. |
| RELEVÂNCIA (PARA NEGÓCIO) | Alta. |
| RISCO (PARA O PROJETO) | Alto. |
*** 
  
### IDENTIFICAÇÃO DO PREÇO
|   [RF007]   | IDENTIFICAÇÃO DO PREÇO |
| --- | --- |
| NÚMERO DO REQUISITO | 7 |
| DESCRIÇÃO | Após o escaneamento do produto, o usuário deverá identificar o preço para que o sistema faça a atualizaçã e a comparação do preço |
| CLASSIFICAÇÃO | Requisito Funcional. |
| DEPENDÊNCIAS | [RF001]; [RF002]; [RF003] e [RF005] |
| ESFORÇO (PARA DESENVOLVER) | Alto. |
| RELEVÂNCIA (PARA NEGÓCIO) | Alta. |
| RISCO (PARA O PROJETO) | Alto. |
*** 
