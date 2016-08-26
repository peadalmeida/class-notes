# Modelagem Dimensional
Prof. Sandro Jerônimo de Almeida

[Slides](http://webdav.sistemas.pucminas.br:8080/webdav/sistemas/sga/20162/1112312_DW_Parte1.pdf)

- Uma técnica de projeto lógico freqüentemente usada para Data Warehouse, cujo 
principal objetivo é apresentar o dado em uma arquitetura padrão e intuitiva, que permita acessos de alta performance.
    + Busca apresentar os dados em um modelo padronizado e intuitivo, que permita o entendimento por parte de usuários, bem como alto desempenho de acesso.
- Forma de modelagem onde as informações se relacionam de maneira que podem ser representadas metaforicamente como um cubo. 

### Elementos da Modelagem Dimensional
- Assuntos que serão analisados. Acontecimento merecedor de análise e controle na organização. 
- Variáveis de análise de um acontecimento:
    + **Quem** executou o acontecimento
    + **Onde** acontece
    + **Quando** acontece
    + **O quê** participa do acontecimento
- Medidas que são analisadas em um assunto de acordo com as variáveis de análise. 
    + Quantas vezes aconteceu?

### Granularidade
Granularidade diz respeito ao nível de detalhe ou de resumo contido nas unidades de dados existentes no data warehouse. Quanto maior o nível de detalhes, menor o nível de granularidade. O nível de granularidade afeta diretamente o volume de dados armazenado no Data Warehouse e ao mesmo tempo o tipo de consulta que pode ser respondida.

- Nível de detalhe ou de resumo contido nas unidades de dados existentes na tabela  fato.
- A granularidade de dados refere se ao nível de sumarização dos elementos e de detalhe disponíveis nos dados, considerando o mais importante aspecto do projeto de um  Data Warehouse.
- Quanto mais detalhe existir nos dados, mais fina será a granularidade. Quanto menos detalhe existir, mais grossa será a granularidade. 
- Definir a granularidade adequada é vital para que o Data Warehouse atenda seus objetivos.
    + Grão em um nível mais detalhado (Granularidade Fina)
        * Vantagem: O usuário poderá ver a informação em qualquer nível de agregação 
        * Desvantagem: Pode acarretar um aumento muito grande do volume de dados armazenado. Prejuízo de perfomance.
    + Grão em um nível mais alto (Granularidade Grossa)
        * Vantagem: Menor volume de dados armazenado
        * Desvantagem: Usuário ficará impossibilitado de realizar consultas mais detalhadas. 
- Afeta diretamente o volume de dados armazenado e ao mesmo tempo o tipo de consulta que pode ser respondida.
- Um grão corresponde a um registro na tabela fato. 







