# Análise de Vendas - Lojas Ferao.Distrib LTDA (2017-2019)
* Neste Dashboard, analisamos tendências de vendas utilizando DAX e algumas modificações no Power Query para facilitar o desenvolvimento de métricas, KPIs e Dashboard.

# Pág1/Pág2 - Análise de Produtos

*  Filtros laterais com hierarquia de data, cidade, grupo, supervisor, gerente, vendedor e limpador de segmentação (todos sincronizados).
*  Cards com valor total, NFS emitidas, total de clientes atendidos, produtos disponíveis e categorias.
*  Gráfico de Pizza com representatividade por setor.
*  Gráfico de barras verticais com valor total de venda por grupo de produtos.
*  Gráfico de colunas com o Peso Total (KG) vendido.
* Página 1
  ![image](https://github.com/nicolaskra/ferao_distrib/assets/144272226/732c09f5-31b8-4372-8aa5-fb6919ca602c)
* Página 2
  ![image](https://github.com/nicolaskra/ferao_distrib/assets/144272226/f39e6c8f-2d50-4e98-97a8-3a8cc178812a)

#  Pág1/Pág2 - Insights

*  Observamos que a venda foi dominada pelo setor de alimentos, representando 91,39%. Isso nos leva a refletir: as bebidas representaram apenas 8,61%. Será que devemos ampliar nosso setor de bebidas? Ou há outra causa para essa discrepância? Vale uma análise mais detalhada pelo time comercial.
*  A farinha de trigo representa 24,98% das vendas totais de alimentos, um resultado excelente. Para comparação, a representatividade de Óleos foi de 12,21% e Fermentos, 12,29%. Ou seja, a farinha de trigo superou ambos combinados.
*  Foi observado também que existem diversos produtos com valor de venda zerado. Após uma análise mais profunda, vimos que o total de produtos distintos vendidos foi de 798, enquanto na base de dados constam mais de 1.938 produtos, muitos dos quais não foram vendidos. Esse dado deve ser passado ao time de DBA e comercial para avaliar se esses produtos têm estoque e não foram vendidos ou se saíram de linha.

#  Pág3/Pág4 - Análise de Vendedores

*  Filtros laterais com hierarquia de data, cidade, grupo, supervisor, gerente, vendedor e limpador de segmentação (todos sincronizados).
*  Cards com quantidade de supervisores, gerentes e vendedores.
*  Scroller com o ranking de vendedores e o total de venda.
*  Gráfico de Pizza com a representatividade de cada equipe em % e valor total (dicas de ferramentas com mais dados).
*  Gráfico de barras verticais com drill down de equipe - supervisores - gerentes - vendedores, comparando vendas x vendas LY.
*  Árvore Hierárquica com fonte valor de venda, permitindo análise do desempenho de cada hierarquia.

* Página 3
  ![image](https://github.com/nicolaskra/ferao_distrib/assets/144272226/f06b5093-b546-44d3-9a50-abaeabdb75f3)
* Página 4
  ![image](https://github.com/nicolaskra/ferao_distrib/assets/144272226/cbc147bb-24a2-4432-ada5-b545eed7343a)

# Pág3/Pág4 - Insights

*  O varejo domina as vendas com 48,56% de representatividade.
*  No momento atual (sem nenhum filtro aplicado), todos os segmentos e praticamente todos os vendedores já ultrapassaram o valor de venda do último ano, um ótimo sinal.
*  O segmento online teve o maior aumento de vendas, crescendo 11% em relação ao LY. Já o Varejo obteve 5,30% e Distribuidores, 4,90%.
*  Carla Ferreira tem o maior valor de ticket médio por cliente, R$40.934.
*  Estevan Souze teve o melhor percentual de crescimento de vendas, 26,98%, mas é importante considerar que o volume de vendas dele é muito menor que o dos outros vendedores. Ele é seguido por Matheus Costa, com 23,07%.

