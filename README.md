#CONCLUSÃO 

Para este projeto, coletamos dados de várias fontes, incluindo Netflix, Rotten Tomatoes Movies e Rotten Tomatoes Critic Reviews, para realizar uma análise combinada dos títulos disponíveis na Netflix e suas respectivas avaliações no Rotten Tomatoes. Para atingir esse objetivo, implementamos uma estratégia baseada em ciência de dados que consistiu nas etapas a seguir:

Carregamento e Limpeza de Dados: Para garantir que trabalhássemos com um conjunto de dados limpo e confiável, começamos carregando os arquivos CSV e removendo dados duplicados e ausentes. Para evitar problemas e erros durante as análises, essa etapa foi fundamental.

Integração de Dados: Colunas comuns, como os títulos de filmes ou séries, serviram de base para a integração de vários datasets. Para compilar dados da Netflix, usamos a função merge do Pandas.para combinar os dados da Netflix e Rotten Tomatoes, criando um único dataframe com as informações pertinentes.

Exploração de Dados: Em seguida, examinamos os dados para encontrar as respostas a dez perguntas de pesquisa. Para encontrar tendências, como os gêneros mais populares ou a média de avaliações por ano de lançamento, foi usado um método de agrupamento. Além disso, contamos frequências e ordenamos os dados para destacar os títulos e diretores mais bem avaliados na plataforma.

Visualização de Dados: Criamos gráficos de barras e histogramas usando as bibliotecas Matplotlib e Seaborn para facilitar a interpretação dos resultados. Essas visualizações nos ajudaram a entender a distribuição das avaliações e a popularidade dos gêneros.

Regressão Linear: Usamos um modelo simples para verificar a relação entre o ano em que os filmes foram lançados e as avaliações deles no Rotten Tomatoes. Ao usar a regressão, foi possível determinar se havia uma tendência nas avaliações ao longo dos anos, demonstrando o quanto essa análise pode revelar correlações significativas.

Conclusão da Análise: A Netflix oferece uma ampla gama de gêneros, com destaque para documentários e comédias, de acordo com os resultados. Além disso, observamos que os filmes que receberam mais críticas geralmente recebem avaliações mais equilibradas, e a plataforma possui um conjunto considerável de filmes bem avaliados no Rotten Tomatoes. Nos chegamos a esses resultados de forma eficiente graças às ferramentas de análise de dados.

Integrantes do Grupo:

Gabriel Fernandes Doms RM 98630
Felipe Masera Terra RM 99405
