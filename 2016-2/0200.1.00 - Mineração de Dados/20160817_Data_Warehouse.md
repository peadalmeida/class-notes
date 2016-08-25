# Data Warehouse
Prof. Sandro Jerônimo de Almeida

O Data Warehouse se trata da mais importante tecnologia existente no desenvolvimento de soluções de Business Intelligence (BI). Ela é a base para o armazenamento das informações necessárias para a utilização por gestores e analistas na tomada de decisão. O Data Warehouse possui estrutura e características que suportam análise de grande volumes de dados.

![data-warehouse](https://cloud.githubusercontent.com/assets/1865456/17952629/b901a628-6a42-11e6-971e-c98c67dae1af.jpg)

- **Fonte de Dados:** Abrange todos os dados de origem que irão compor as informações do Data Warehouse. Compreende os sistemas OLTP, arquivos em diversos formatos (XLS, TXT, etc), sistemas de CRM, ERP, entre vários outros. 

- **ETL:** O ETL, do inglês Extract Transform and Load, é o principal processo de condução dos dados até o armazenamento definitivo no Data Warehouse. É responsável por todas as tarefas de extração, tratamento e limpeza dos dados, e inserção na base do Data Warehouse. 

- **Staging Area:** A Staging Area é uma área de armazenamento intermediário situada dentro do processo de ETL. Auxilia a transição dos dados das origens para o destino final no Data Warehouse. 

- **Data Warehouse:** essa é a estrutura propriamente dita de armazenamento das informações decisivas. Apenas os dados com valor para a gestão corporativa estarão reunidos no Data Warehouse

- **Data Mart:** O Data Mart é uma estrutura similar ao do Data Warehouse, porém com uma proporção menor de informações. Trata-se de um subconjunto de informações do Data Warehouse que podem ser identificados por assuntos ou departamentos específicos. O conjunto de Data Marts em conformidade dentro da organização compõe o Data Warehouse. 

- **OLAP:** O OLAP, do inglês Online Analytical Processing, na arquitetura de um Data Warehouse se refere as ferramentas com capacidade de análise em múltiplas perspectivas das informações armazenadas. 

- **Data Mining:** Data Mining ou Mineração de Dados, se refere as ferramentas com capacidade de descoberta de conhecimento relevante dentro do Data Warehouse. Encontram correlações e padrões dentro dos dados armazenados.

O fluxo das atividades nessa arquitetura se inicia com a extração dos dados das origens. Esses dados são então armazenados temporariamente na Staging Area, onde são tratados com as regras e padrões predeterminados para então prosseguir para a etapa de carga (Load), em que os dados são carregados no Data Warehouse. Por fim, essas informações são normalmente consultadas através de ferramentas de análises (OLAP) ou ferramentas de mineração (Data Mining) para encontrar, assim, as respostas e insights necessários para a tomada de decisão. 

Portanto, com essa visão geral da arquitetura do Data Warehouse, é possível conceber e entender melhor o funcionamento dessa tecnologia que há anos vem se destacando no mercado como uma das mais importantes estruturas de armazenamento de informações estratégicas. Cabe as empresas perceberem o valor agregado ao Data Warehouse e antecipar a concorrência no que tange a gestão das informações que fornecem competitividade e inteligência no mercado, além de favorecerem o crescimento e alcance de resultados positivos na organização.