# Processamento de linguagem natural com Python
 <br><br>
Dataset utilizado: https://www.kaggle.com/datasets/marlesson/news-of-the-site-folhauol
<br><br>
Pontos cobertos no documento:
<br><br>
	**Implementar técnicas de lematização**
- Download dos pacotes necessários para tokenização e stemming usando nltk
- Atualização do spacy e instalação do modulo pt_core_news_lg
- Download dos dados diretamente do kaggle
- Tokenização e o stemming dos textos usando funções do nltk
- Lematização usando o spacy
- Comparação entre stemming e lematização
<br><br>
	**Construir um modelo de reconhecimento de entidades (NER) usando Spacy**
- Extração de entidades dos textos e filtro por Organização
- Nuvem de entidades para cada tópico obtido (no final do notebook)
<br><br>
    **Criar modelos utilizando vetorização de textos baseado em Bag of Words**
- Quando adotamos uma estratégia frequentista para converter textos em vetores, podemos fazê-lo de diferentes maneiras. Motavações para adoção do TF-IDF frente as duas outras opções.
- Criação do vetor de TF-IDF para cada texto. 
- Extração de tópicos usando o algoritmo de LDA.
- Visualização via LDAVisa.
- Nuvem de palavras para cada um dos 9 tópicos criados.
- Descrição para cada tópico extraído, comparação semântica e valor agregado.
<br><br>
	**Criar modelos baseados em Word Embedding**
- Usamos TF-IDF para gerar os vetores que servem de entrada para o algoritmo de LDA. Descrição de quais seriam os passos para gerar vetores baseados na técnica de Doc2Vec.
- Em uma versão alternativa desse projeto, optamos por utilizar o algoritmo de K-Médias para gerar os clusters (tópicos). Comaração das abordagens TF-IDF e Doc2Vec) para o processo de vetorização.
- Leia o artigo "Introducing our Hybrid lda2vec Algorithm" (https://multithreaded.stitchfix.com/blog/2016/05/27/lda2vec/#topic=38&lambda=1&term=). Estudo do algoritmo lda2vec que pretende combinar o poder do word2vec com a interpretabilidade do algoritmo LDA.