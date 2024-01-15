# GETRECOM  

## *Explicação*  
Segue o código desenvolvido em Python para o projeto do meu trabalho de graduação, focado na aplicação de Business Intelligence e Machine Learning para a categorização de clientes e na associação de seus produtos para a criação de modelos personalizados de produtos. O trabalho aderiu à metodologia CRISP-DM, passando pelas seguintes fases: compreensão do negócio, análise dos dados, preparação dos dados, modelagem, avaliação e implementação.  
## *Entendimento do negócio*  
Abordar a questão que envolve a utilização combinada de Machine Learning (ML) e Business Intelligence (BI) para implementar algoritmos de agrupamento e associação nos dados dos clientes. O objetivo é proporcionar recomendações precisas de produtos ao analisar a base de dados de uma empresa de médio porte que oferece cursos direcionados a profissionais executivos de alta hierarquia.  
## *Entendimento dos dados*
Uma base de dados em formato CSV fornecida pela empresa, apresentando informações estruturadas e anonimizadas para preservar a identidade dos clientes. Esta base contém aproximadamente 800 mil registros de transações, com 24 colunas de atributos, abrangendo o período de setembro de 2016 a fevereiro de 2023.  
## *Preparação dos dados* 
O processo de tratamento dos dados incluiu a eliminação de informações dispensáveis e a verificação de valores ausentes. Foi aplicada a técnica/imputação condicional para preenchimento de dados em atributos nominais e numéricos. Como resultado, a base de dados tratada apresenta uma redução para 103.140 mil linhas e 17 colunas.  
## *Modelagem*  
Foram empregados algoritmos de agrupamento, visando a formação de grupos de clientes com atributos semelhantes, e algoritmos de associação para identificar a relação entre os produtos adquiridos pelos clientes. Dentre os algoritmos de agrupamento, foram utilizados o K-means, Agrupamento Hierárquico, DBSCAN e MeanShift. A escolha do modelo ideal baseou-se nos critérios de Coeficiente de Silhueta e Índice Davies-Bouldin, e o K-means destacou-se como a opção preferencial. É relevante mencionar o uso de UMAP, uma técnica de redução de base de dados, para viabilizar a execução de alguns algoritmos e proporcionar visualização gráfica dos agrupamentos.
  
Na fase de associação, os algoritmos Apriori, ECLAT e FP-Growth foram empregados, com a preferência pelo Apriori. A partir da combinação do K-means e Apriori, foi desenvolvido o modelo de recomendação.  
## *Avaliação*  
Com base nos resultados dos algoritmos, foi realizada uma análise para avaliar a relevância e verificar se o objetivo inicial de desenvolver um algoritmo capaz de agrupar e recomendar produtos foi alcançado.  

## *Implementação*  
Exibição dos resultados a partir do Power BI.






