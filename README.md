# Kmeans

O algoritmo K-means é uma técnica popular de aprendizado não supervisionado utilizada em análise de agrupamento. Ele agrupa dados em clusters, onde os pontos de dados dentro de um mesmo cluster são mais semelhantes entre si do que com pontos de outros clusters. O objetivo do K-means é encontrar k centróides (pontos representativos) de forma que a soma dos quadrados das distâncias entre os pontos e seus centróides seja minimizada.

A aplicação do K-means pode ser vista em diversos domínios, incluindo a análise de dados biológicos, segmentação de clientes, compressão de imagens, entre outros. 

## Projeto - Pétalas e Sépalas
No contexto específico do estudo de caso de reconhecimento de pétalas e sépalas usando K-means, utilizando o conjunto de dados da íris (Iris dataset). O conjunto de dados da íris consiste em medidas de comprimento e largura das sépalas e pétalas de três espécies de flores de íris: setosa, versicolor e virginica. O objetivo é agrupar essas flores com base nessas medidas. 



# ETAPAS
1 - Preparação dos dados:
- Coletar e carregar o conjunto de dados da íris.
- Extrair as características relevantes, como comprimento e largura da sépala e pétala.

2 - Normalização dos dados:
- Normalizar as características, se necessário, para garantir que todas tenham a mesma escala.

3 - Escolha do número de clusters (k):
- Neste caso, como sabemos que existem três espécies de íris, podemos escolher k=3.

4 - Treinamento do modelo K-means:
- Aplicar o algoritmo K-means aos dados normalizados, procurando os centróides que melhor representam os clusters.

5 - Atribuição dos clusters:
- Atribuir cada instância de dados ao cluster mais próximo (com base na distância euclidiana até os centróides).

6 - Análise e interpretação:
- Analisar os clusters formados e interpretar os resultados. Cada cluster deve representar uma espécie de íris.

7 - Avaliação do modelo:
- Para o conjunto de dados da íris, como sabemos as espécies verdadeiras, podemos avaliar o desempenho do modelo comparando os clusters atribuídos com as espécies reais.

# Projetos
- Pétalas e Sépalas
- Peso e Colesterol

