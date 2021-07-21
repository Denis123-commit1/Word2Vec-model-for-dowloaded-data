# Word2Vec-model-for-dowloaded-data

English: Build and visualize Word2Vec model with Gensim
This code belongs to the "Build and Visualize Word2Vec Model on Amazon Reviews" blog post.

Word2vec is a very popular Natural Language Processing technique nowadays that uses a neural network to learn the vector representations of words called "word embeddings" in a particular text.

In this tutorial, we will use the excellent implementation of word2vec from the gensim package to build our word2vec model. We will use t-Distributed Stochastic Neighbor Embedding (t-SNE) in sklearn to visualize the learned embeddings vectors.

Requirements
Python 3.9
Jupyter Notebook
gensim
numpy
pandas
natural language toolkit (nltk)
Dataset
We will use the Amazon review corpus on Health and Personal Care. The dataset is in json format and contains 346,355 reviews.

Model visualization
we visualize the learned embeddings using t-SNE. t-SNE is a tool for data visualization that reduces the dimensionality of data to 2 or 3 dimensions so that it can be plotted easily.

Word2vec plot image

Most similar words
One way to check if we have a good word2vec model is to use the model to find the most similar words to a specific word. For that, we can use the most_similar function that returns the 10 most similar words to the given word. Let's find the most similar words to the word blue.

corpus was taken from this link: http://jmcauley.ucsd.edu/data/amazon/ ("Health and Personal Care")

На русском: # Word2Vec-model-for-dowloaded-data

Создавайте и визуализируйте модель Word2Vec с помощью Gensim
Этот код относится к сообщению блога «Создание и визуализация модели Word2Vec в обзорах Amazon».

Word2vec - это очень популярный в настоящее время метод обработки естественного языка, который использует нейронную сеть для изучения векторных представлений слов, называемых «встраиваниями слов» в конкретный текст.

В этом руководстве мы будем использовать отличную реализацию word2vec из пакета gensim для построения нашей модели word2vec. Мы будем использовать t-распределенное стохастическое соседнее вложение (t-SNE) в sklearn для визуализации изученных векторов встраивания.

Требования
Python 3.9
Jupyter Notebook
gensim
numpy
pandas
natural language toolkit (nltk)
Dataset
Мы будем использовать корпус обзоров Amazon по вопросам здоровья и личной гигиены. Набор данных в формате json и содержит 346 355 отзывов.

Визуализация модели
мы визуализируем изученные вложения с помощью t-SNE. t-SNE - это инструмент для визуализации данных, который уменьшает размерность данных до двух или трех измерений, чтобы их можно было легко построить.

Word2vec изображение графика

Самые похожие слова
Один из способов проверить, есть ли у нас хорошая модель word2vec, - это использовать модель для поиска слов, наиболее похожих на определенное слово. Для этого мы можем использовать функцию most_similar, которая возвращает 10 слов, наиболее похожих на данное слово. Давайте найдем слова, наиболее похожие на слово синий.

корпус взят по этой ссылке: http://jmcauley.ucsd.edu/data/amazon/ («Здоровье и личная гигиена»)
