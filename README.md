# NLP

* pytorch ner
* Графы знаний ODS https://ods.ai/tracks/kgcourse2021/blocks/7b7e102d-f61e-4349-a8ea-440f6dd50bb4
* yargy parser https://www.youtube.com/watch?v=NQxzx0qYgK8&ab_channel=%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D0%B5%D0%BD%D0%B0%D1%83%D0%BA%D0%B8
* Графы. NLP https://www.kaggle.com/pavansanagapati/knowledge-graph-nlp-tutorial-bert-spacy-nltk
* класификация logreg 
* поиск по документам elastic search gensim.bm25
* spacy ГРАФЫ knowledge grapf https://www.analyticsvidhya.com/blog/2019/10/how-to-build-knowledge-graph-text-using-spacy/
* knowledge graph https://neptune.ai/blog/web-scraping-and-knowledge-graphs-machine-learning
* кластеризация dbscan 
* ruGPT-3 (https://colab.research.google.com/drive/1bwNxmVJMJ3x_N5ylS-nylkQpHUAF0DES?usp=sharing ; )
* парафраз https://habr.com/ru/post/564916/ + https://github.com/avidale/python-ruwordnet/ + https://github.com/avidale/dependency-paraphraser
* обучение word2vec glove 
* rnn генерация высоцкий на уровне слов 
* NER deeppavlov http://docs.deeppavlov.ai/en/master/features/models/ner.html#multilingual-bert-zero-shot-transfer
* beam search
* negativ log likehood
* skip connection 
* relation extraction
* shap values for text
* поиск дубликатов | алгоритм шинглов minHASH
* bert sber https://huggingface.co/sberbank-ai/sbert_large_nlu_ru
* чат бот постит суммаризацию новостей
* скрытое состояние RnN как эмбединг предложения
* суммаризация textrank + spacy ; bert; autoencoder; kmeans(кластеризацию + предл ближе к центроиды
https://colab.research.google.com/github/BritneyMuller/colab-notebooks/blob/master/Easy_Text_Summarization_with_BART.ipynb
https://medium.com/analytics-vidhya/text-summarization-using-spacy-ca4867c6b744
https://medium.com/genesis-media/how-we-create-headlines-in-the-russian-language-by-means-of-ml-e859b299ddc5
* исправление опечаток ЛИВЕНШТЕЙН и fastapi,word, jamspell, autocorrect
* ПЕРЕПИСЫВАНИЕ ТЕКСТА word2vec svd lsa # https://freelancehunt.com/out/https%3A%2F%2Fhabr.com%2Fru%2Fpost%2F564916%2F
* Тематическое моделирование
* text to speech https://github.com/tesemnikov-av/deep_learning_2018-19/blob/master/21.%20Text2Speech/%5Bseminar%5Dtext_to_speech.ipynb
* извлечение именованных сущностей
* генерация текста 
* чат бот 
* вопросы ответы mail ru
* heatmap достоевский и ильф 
* граф связей персонажей

LsA 

### Сумаризация текста
Берт:
https://habr.com/ru/post/566486/
Text rank 
http://igorshevchenko.ru/blog/entries/textrank

сабсэмплинн смотреть формулу реже брать часто встречающие слова и чаще реже встречающие типа графика закон ципфа

разложение ХОЛЕЦКОГО

девергенция кульбака лейблера это расстояние между распределениями ( или между векторами если их нормировать)


word2vec для аугментации данных или переписыва6ия романа 


https://simpletransformers.ai/docs/classification-models/
https://huggingface.co/transformers/training.html

PmI: для термов; взаимная поточечная информация: теория информации - те слова которые реже встречаются вместе, имеют больше информации! анализ романов те что часто встречаются коллокациинапример сан франциско

Разметка тональности слов на русском

https://github.com/Helsinki-NLP/XED/blob/master/Projections/ru-projections.tsv

Классификация новостных текстов 

https://www.kaggle.com/c/lenta-ru-ozon-2020/data?select=lenta-ru-train.csv

предсказа6ие связей в графах 
https://docs.ampligraph.org/en/1.2.0/index.html

Deeppavlov
Rasa

word2vec домножить на коэфицент tf idf

сглаживание КНЕЗЕРА НЕЯ




d Notepad
https://gist.github.com/avidale/cacf235aebeaaf4c578389e1146c3c57#file-bert-ner-ru-ipynb

Индексирование
https://www.youtube.com/watch?v=ZuUnlJFWPkA&list=RDCMUCMH211UPVhGz5WR9sNCatcg&index=1&ab_channel=VolodyaMozhenkov

Биг О натация


Лекции NLP

Градиентный бусины как учатся деревья
http://mathprofi.ru/statisticheskie_gipotezy.html

Суммаризация текст - извлечение сущностей
Несмещенность 
Метод Главных компонен
Оптимизаторы Adam vs RMSProp
Stat quest МНК ГРАДИЕНТНЫЙ БУСТИНГ
Обучение с подкреплением
AUTO ML
SOLID принципы

Entropy gini https://www.coursera.org/learn/advanced-machine-learning-methods/lecture/IW9H4/kritierii-informativnosti

Skewness and Kurtosis
Вырожденная и невырожденная матрица
Нулевое распределение

https://tproger.ru/translations/preparing-for-data-science-interview/
https://github.com/alexeygrigorev/data-science-interviews/blob/master/technical.md

Np полные задачи
Аутоэнкодеры 
Тренажер SQL
Q LEARNING
Attention DeppLearning

Коллеги, я правильно понимаю что query и keys это: 1. Слово и Его перевод в механизмах внимания 2. Слово и это же слово в механизмах само-внимания? А values это их мера сходства (произведение).
