# Análise de um dataset de uma empresa de eletrônicos 
Repositório usado para mostrar que vários problemas de um cientista de dados podem ser resolvidos sem algoritmos de machine learning, apenas com uma boa análise dos dados

## Setup

Os dados foram obtidos a partir de uma empresa americana, infelizmente não consegui ainda dados abertos no Brasil e também não sei qual empresa é, acredito ser uma informação sigilosa. Conta com quase 200 mil ordens de compra, separadas por mês, durante um ano.

## Data Cleaning:

Usando Python e bibliotecas como Pandas e Matplotlib, somos capaz de analisar os dados e responder algumas dúvidas de negócios. O dataset é composto por colunas, cada uma indicando o tipo do produto comprado, o custo, o endereço da compra, o código da compra, data, etc.

Muitas vezes os dados vêm da empresa com falhas, com dados em branco, com formatos diferentes, portanto a primeira atribuição de um cientista de dados é "limpar" os dados, algumas etapas:
- Retirar valores não numéricos (NaN) no dataframe 
- Remover linhas vazias
- Mudar o tipo da coluna para o formato desejado

Após limpar os dados, fica muito mais fácil e direto trabalhar com os mesmos. Algumas perguntas que podem ser levantadas em um dataset empresarial e suas respectivas respostas:
- Qual o melhor mês para as vendas? Quanto foi ganho este mês?
- Qual cidade foi a melhor em vendas?
- Qual seria o melhor horário para exibir anúncios, baseado na hora que as compras são efetivadas?
- Quais produtos são mais vendidos em conjunto?
- Qual é o produto mais vendido? Porquê esse produto é o mais vendido?

Alguns links e materiais que usei como auxílio/motivação:

https://stackoverflow.com/questions/14762181/adding-a-y-axis-label-to-secondary-y-axis-in-matplotlib
https://stackoverflow.com/questions/43348194/pandas-select-rows-if-id-appear-several-time
https://stackoverflow.com/questions/27298178/concatenate-strings-from-several-rows-using-pandas-groupby
https://stackoverflow.com/questions/52195887/counting-unique-pairs-of-numbers-into-a-python-dictionary
https://youtu.be/eMOA1pPVUc4