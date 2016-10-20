## Regras de Associação
Prof. Sandro Jerônimo de Almeida
[Slides]()

### Introdução:

- Modelo extensivamente estudado pelas comunidades de bancos de dados e aprendizado de máquina
- Assume que os dados não categoricos; portanto, não se aplica a dados numéricos
- Inicialmente utilizado na análise de cesta de compras em supermercados (Market Basket Analysis) para determinar como os itens comprados por clientes 
estão relacionados
- A tarefa de associação tem como objetivo encontrar elementos que implicam na presença de outros elementos em uma mesma transação, ou seja, encontrar relacionamentos ou padrões freqüentes entre conjuntos de exemplos
- Portanto, Regras de Associação representam padrões existentes nas transações de um banco de dados

### Atributos Relevantes

As Regras de Associação podem ser fracas e até absurdas. Um exemplo disso pode ser observado na tabela acima onde um único cliente comprou um livro de Física e também comprou um suco. Isso não poderia ser interpretado como uma regra de certeza absoluta para outros casos.

Para avaliar a força de uma regra são utilizados dois termos: **Suporte** e **Confiança**. Em análise associativa existem várias definições para os conceitos de suporte e confiança. Considere X e Y como sendo itens de compra. O método mais empregado para o cálculo do suporte é a razão entre o número de registros contendo X e Y e o total de registros, conforme segue:



