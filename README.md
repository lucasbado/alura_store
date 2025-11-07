📊 AluraStore Brasil - Análise de Vendas (Challenge 1)
Descrição do Projeto
Este projeto consiste na análise de dados de vendas de quatro diferentes filiais da AluraStore Brasil (Loja 1, Loja 2, Loja 3 e Loja 4). O objetivo central do desafio é realizar uma análise comparativa de desempenho entre as lojas, considerando fatores como faturamento, volume de vendas, custo de frete e satisfação do cliente, para fornecer uma recomendação estratégica sobre qual loja seria mais vantajosa para ser vendida ou mantida.

Estrutura do Notebook e Análises
O notebook AluraStoreBrasil (2).ipynb aborda as seguintes etapas de análise:

1. Análise do Faturamento
Calcula o Faturamento Total de cada loja com base na coluna Preço:

Loja 1: R$ 1.534.509,12

Loja 2: R$ 1.488.459,06

Loja 3: R$ 1.464.025,03

Loja 4: R$ 1.384.497,58

2. Análise da Quantidade de Produtos Vendidos
Analisa a quantidade total de produtos vendidos por loja e detalha o volume de vendas por Categoria do Produto. As categorias moveis e eletronicos destacaram-se consistentemente no volume de vendas em todas as lojas.

3. Média de Avaliação das Lojas
Calcula e compara a Média de Avaliação de Compra por Categoria do Produto em cada loja, oferecendo um panorama sobre a satisfação dos clientes por tipo de item.

4. Produtos Mais e Menos Vendidos
Identifica o top 10 de Produtos Mais Vendidos e o top 10 de Produtos Menos Vendidos para cada filial. Este ponto é crucial, pois, na Loja 3, a margem mínima de vendas dos produtos menos vendidos é de 35 unidades, sugerindo um fluxo de vendas mais equilibrado.

5. Frete Médio por Loja
Analisa o Frete Médio por loja, um indicador de custo logístico:

Loja 1: Frete Médio de R$ 39,16

Loja 4: Frete Médio de R$ 31,01

Conclusão e Recomendação Estratégica
A análise comparativa entre faturamento e custos logísticos (frete) levou à seguinte conclusão:

A recomendação é a venda da Loja 1. Embora a Loja 1 seja a líder em faturamento (R$ 1.534.509,12), ela também apresenta o frete médio mais alto (R$ 39,16). Este alto custo logístico impacta significativamente a margem de lucro, tornando-a menos atrativa para ser mantida.

Por outro lado, a Loja 3 se mostra a mais lucrativa. Mesmo com um faturamento total um pouco menor, ela possui um frete médio mais baixo (R$ 34,04) e um fluxo de vendas mais consistente, inclusive para os produtos de menor saída, garantindo uma margem de lucro mais positiva.

Tecnologias Utilizadas
Python

Pandas: Manipulação e análise dos dados.

Matplotlib: Visualização de dados (gráficos de pizza, linha e barra).

Seaborn: Geração do Heatmap de concentração de vendas por localização.

Como Executar o Projeto
Clone o repositório (se estiver em um) ou baixe o arquivo .ipynb.

Certifique-se de ter as bibliotecas pandas, matplotlib e seaborn instaladas em seu ambiente Python.

Abra o notebook AluraStoreBrasil (2).ipynb em um ambiente como Google Colab ou Jupyter Notebook.

Execute todas as células sequencialmente para replicar a importação de dados e as análises.
