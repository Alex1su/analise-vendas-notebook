# analise-vendas-notebook
## Introdução

O preço de um laptop pode variar significativamente entre marcas e modelos, sendo influenciado por fatores como especificações técnicas, softwares inclusos e até o design do produto. Este projeto tem como propósito investigar quais variáveis exercem maior influência sobre o preço dos laptops, utilizando dados reais coletados de um site de e-commerce.

## Objetivo
O objetivo deste projeto é identificar os principais fatores que impactam o preço dos laptops.
A análise busca responder perguntas como:

A marca realmente influencia o preço?

  Especificações técnicas como memória RAM, processador e armazenamento têm peso maior?
  
O número de softwares pré-instalados e acessórios também afeta o valor final?

## Metodologia

Fonte dos dados: Flipkart.com
Ferramenta de coleta: Instant Data Scraper (extensão do Chrome para extração automatizada de dados web, sem necessidade de codificação).

Etapas do processo:

-Coleta e exportação dos dados brutos.

-Limpeza e padronização do dataset (remoção de duplicatas, tratamento de nulos e inconsistências).

-Análise exploratória de dados (EDA) para identificar padrões e correlações.

-Criação de visualizações para interpretação dos resultados.

## Estrutura da Análise

1. Entendimento dos dados – verificação das variáveis disponíveis e suas categorias.
2. Limpeza e preparação – tratamento de dados ausentes e conversão de tipos.
3. Análise descritiva – resumo estatístico e distribuição dos preços.
4. Correlação entre variáveis – identificação de fatores que mais afetam o preço.
5. Visualizações – gráficos e dashboards para comunicar os insights.
6. Conclusões e aprendizados – resumo dos fatores mais relevantes e implicações de mercado.

## Visão Geral dos Dados
O conjunto de dados contém informações sobre:

-Marca

-Memória RAM

-Processador (velocidade e geração)

-Capacidade de armazenamento

-Softwares pré-instalados

-Acessórios incluídos no pacote

-Design e aparência do laptop

A análise demonstrou que marca, memória RAM e processador são os principais fatores associados a preços mais altos, seguidos por armazenamento e quantidade de softwares instalados.

## Analise Descritiva
Forneceu uma visão geral de dados destacando a média por marca mostrou que Alienware e Apple lideram as faixas de maior valor, enquanto marcas como Acer e Lenovo concentram-se em segmentos intermediários. O resultado reforça que o posicionamento de marca influencia diretamente o preço final dos laptops.

<img width="746" height="400" alt="visualization (2)" src="https://github.com/user-attachments/assets/2386a825-9fa2-4b01-a9eb-f80a1f1d55b6" />







O gráfico abaixo apresenta a participação de cada tipo de memória RAM (DDR3, DDR4 e DDR5) entre os laptops analisados. Observa-se que:

<img width="746" height="400" alt="visualization" src="https://github.com/user-attachments/assets/5a8b1123-a93b-46dc-9909-27ce8fbc1610" />

- DDR5 representa 45,30% dos modelos, sendo a tecnologia mais presente no conjunto de dados.
- DDR4 aparece em 32,69% dos laptops, consolidando-se como uma opção intermediária em termos de custo e desempenho.
- DDR3 corresponde a 22,01%, indicando menor presença devido à defasagem tecnológica.

Esses resultados demonstram uma tendência de atualização do mercado para memórias mais modernas, como a DDR5, que oferecem maior velocidade de processamento e eficiência energética.
Além disso, a predominância de laptops com DDR5 ajuda a explicar a elevação das médias de preço, visto que equipamentos com esse tipo de memória tendem a estar em faixas de desempenho mais altas.




