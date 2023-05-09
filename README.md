# MovieLens-Neural-Collaborative-Filtering-NSF


* MovieLens_Popularity_Model.ipynb - ноутбук с baseline моделью
* MovieLens_Neural_Collaborative_Filtering.ipynb - основной ноутбук с нейросетью, которая обучает эмбеддинги фильмов и пользователей
* Embeddings.ipynb - проверка полученных эмбеддингов (поиск похожих фильмов)

--------------

Веса обученных моделей можно найти на [Google Диск](https://drive.google.com/drive/folders/1sEjRepagyyU-IQ2YOPFxLjrDIGGOLTuw?usp=share_link)


В папке model_weights лежат 2 файла с весами обученной модели:

1) NCF_Drop_32emb_64lin.pt - веса модели: размер эмбеддингов - 32, скрытые линейные слои - (64, 32, 16, 8)
2) NCF_Drop_128emb_256_16lin.pt - веса модели: размер эмбеддингов - 128, скрытые линейные слои - (256, 128, 64, 32, 16)
