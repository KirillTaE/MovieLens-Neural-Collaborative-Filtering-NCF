# MovieLens-Neural-Collaborative-Filtering-NSF

В папке Notebooks лежат 3 файла:

1) MovieLens_Popularity_Model.ipynb - ноутбук с baseline моделью
2) MovieLens_Neural_Collaborative_Filtering.ipynb - основной ноутбук с нейросетью, которая обучает эмбеддинги фильмов и пользователей
3) Embeddings.ipynb - проверка полученных эмбеддингов (поиск похожих фильмов)

--------------

Веса обуученных моделей можно найти на [Google Диск](https://drive.google.com/drive/folders/1sEjRepagyyU-IQ2YOPFxLjrDIGGOLTuw?usp=share_link)



В папке model_weights лежат 2 файла с весами обученной модели:

1) NCF_Drop_32emb_64lin.pt - веса модели: размер эмбеддингов - 32, скрытые линейные слои - (64, 32, 16, 8)
2) NCF_Drop_128emb_256_16lin.pt - веса модели: размер эмбеддингов - 128, скрытые линейные слои - (256, 128, 64, 32, 16)
