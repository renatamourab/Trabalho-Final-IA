**Autor: Renata Moura Barreto**

**Título: Trabalho final para a Disciplina de IA**

**Introdução**

O trabalho propõe a redução do consumo de carne como uma forma de solucionar os objetivos doze (Ação contra a mudança global do clima) e treze (Consumo e produção responsáveis) do Objetivo de Desenvolvimento Sustentável criado pela ONU (Organização das Nações Unidas), destacando a implementação de uma Inteligência Artificial, apelidada de Vegia, capaz de sugerir receitas vegetarianas ou veganas com base nos alimentos disponíveis do usuário. O foco principal é o desenvolvimento e os resultados dessa IA como uma contribuição para o consumo responsável e a redução do impacto ambiental, especialmente no contexto do aquecimento global.

**Metodologia**
Este trabalho utiliza um dataset semelhante ao utilizado por Philip Seif, mas com tratamentos específicos, removendo receitas não vegetarianas para uma análise mais focada. A IA desenvolvida, diferencia-se por apresentar uma linguagem mais humanizada e acolhedora.
A Vegia interage com o usuário, solicitando a inserção de ingredientes e, com base nisso, recomenda cinco receitas. Três abordagens de recomendação foram implementadas e serão comparadas ao longo do trabalho:
  -> k-Nearest Neighbors (k-NN) com vetorização TF-IDF: Utiliza a técnica de vetorização TF-IDF para representar ingredientes como uma matriz. O algoritmo k-NN, com uma abordagem de "força bruta" e distância de cosseno, encontra os 5 vizinhos mais próximos com base nos ingredientes fornecidos pelo usuário.
  -> Similaridade de Jaccard com matriz TF-IDF e PLN: Cria uma matriz TF-IDF com vetorização e processamento de linguagem natural (PLN). Calcula a similaridade de Jaccard entre os ingredientes do usuário e os das receitas na matriz TF-IDF.
  -> Word2Vec com Rede Neural Sequencial: Treina um modelo Word2Vec e utiliza uma rede neural sequencial para calcular a similaridade de cosseno entre os ingredientes do usuário e as receitas.

**Trabalhos Relacionados**
  -> A postagem do site “Kaggle” “food_com-vegetarian-analysis” feita por Philip Seif;
  -> O trabalho de conclusão de curso intitulado como “TCC_Lorenzo” encontrado no site “GitHub” feita por Lorenzo Benedetti;
  -> A postagem “Document Similarity Algorithms Experiment” de Masatoshi Nishimura, encontrada no site “GitHub”;
  -> A postagem “TF-recomm” do site “GitHub” feita por Guocong Song; 
  -> A postagem “hybrid-rs-trainner” do site “GitHub” feita por Felipe Appio.


