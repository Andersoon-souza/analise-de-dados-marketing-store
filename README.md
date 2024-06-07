# Análise de Dados - EDA 

# Marketing Campaign Data Analysis - (Kaggle)


<img src="Arquivo/store.png" alt="store">

Este projeto tem como objetivo analisar os resultados obtidos por uma loja após a implementação de algumas campanhas de marketing e e identificar tendências que possibilitem uma melhora nos resultados da loja. 

## 📂 Conteúdo

1. [Descrição dos Dados](#descrição-dos-dados)
2. [Insights Iniciais](#insights-iniciais)
3. [Conclusão](#conclusão)
4. [Como Executar o Projeto](#como-executar-o-projeto)

## Descrição dos Dados

Este dataset contém dados interessantes sobre o perfil de clientes de uma loja que comercializa: vinhos, frutas, peixes, doces e outros produtos de linha premium. Também contém dados de campanhas de marketing utilizadas pela loja com intuito de compartilhar com seus 
 clientes promoçoes e protudos.

Nosso intuito é tirar insights que possam melhorar as vendas da loja, por meio de uma otimização das campanhas de marketing.

- **ID:** Esta coluna referencia os clientes da loja, cada cliente tem um número identificador único para cada.
- **Year_Birth:**  Contém a data de nascimento do cliente.
- **Education:** Nível de educação do cliente.
- **Marital_Status:** Indica qual situação conjugal do cliente.
- **Income:** Renda anual do cliente.
- **Kidhome:** Informa a quantidade de crianças residentes com o cliente. Considerando menores de 13 anos.
- **Teenhome:** Informa a quantidade de adolescentes residentes com o cliente. Considerando adolescentes aqueles entre 13 anos e 19 anos.
- **Dt_Customer:** Esta coluna retorna a data de cadastro do cliente na base da loja.
- **Recency:** Número de dias em relação a última compra.
- **MntWines:** Quantidade em dólares de vinhos comprados nos últimos 2 anos.
- **MntFruits:** Quantidade em dólares de frutas compradas nos últimos 2 anos.
- **MntMeatProducts:** Quantidade em dólares de produtos de carne comprados nos últimos 2 anos.
- **MntFishProducts:** Quantidade em dólares de produtos de peixe comprados nos últimos 2 anos.
- **MntSweetProducts:** Quantidade em dólares de produtos Sweet adquiridos nos últimos 2 anos.
- **MntGoldProds:** Quantidade em dólares de produtos Gold adquiridos nos últimos 2 anos
- **NumDealsPurchases:** Número de compras feitas com desconto.
- **NumWebPurchases:** Número de compras realizadas através do site da empresa.
- **NumCatalogPurchases:** Número de compras realizadas através do catálogo.
- **NumStorePurchases:** Número de compras feitas diretamente na loja.
- **NumWebVisitsMonth:** Número de visitas realizadas através do site da empresa.
- **AcceptedCmp1:** Indica se o cliente aceitou a oferta na 1ª campanha, se sim retorna (1), caso contrário retorna (0).
- **AcceptedCmp2:** Indica se o cliente aceitou a oferta na 2ª campanha, se sim retorna (1), caso contrário retorna (0).
- **AcceptedCmp3:** Indica se o cliente aceitou a oferta na 3ª campanha, se sim retorna (1), caso contrário retorna (0).
- **AcceptedCmp4:** Indica se o cliente aceitou a oferta na 4ª campanha, se sim retorna (1), caso contrário retorna (0).
- **AcceptedCmp5:** Indica se o cliente aceitou a oferta na 5ª campanha, se sim retorna (1), caso contrário retorna (0).
- **Response:** Indica se o cliente aceitou a oferta na última campanha, se sim retorna (1), caso contrário retorna (0).
- **Complain:** Indica se o cliente fez alguma reclamação nos últimos 2 anos, se sim retorna (1), caso contrário retorna (0).
- **Country:** Indica o país de origem do cliente.


🔗 [Acessar dados completos]((https://www.kaggle.com/datasets/sahilnbajaj/marketing-campaigns-data-set))

## Insights Iniciais

- Os principais produtos da loja são vinhos, tanto em nível de receita quanto em quantidade vendida. 
- A maioria dos clientes possuem uma graduação ou pós.
  
Mais detalhes podem ser encontrados no Jupyter Notebook associado.

## Conclusão

A análise proporcionou insights valiosos sobre o comportamento dos clientes da loja. Duas campanhas tiveram resultados excelentes em termo de receita, embora não tenham desempenhado tão bem nas vendas efetuadas diretamente no site. Os vinhos tiveram destaque em todas as campanhas, muito em razão de não ter um bem-substituto no catalogo de produtos da loja, que é o acontece com os produtos de carne e peixe por exemplo. A uma oportunidade de melhora no canal digital a ser explorada pela empresa quanto as estratégias utilizadas nas duas principais campanhas, se alinhadas com a que teve o maior retorno neste requisito pode render um acrescimo de receita no futuro.


