## Hi there 👋

<!--
**mk13inc/mk13inc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Сертификаты

| Курс | RUS | ENG |
| :--- | -- | -- |
| Инструменты анализа данных | [PDF](certificates/dat_certificate_ru_kovalev_2024-9535-007.pdf) | [PDF](certificates/dat_certificate_en_kovalev_2024-9535-007.pdf) |
| Специалист по Data Science | [PDF](https://github.com/mk13inc/mk13inc/blob/main/certificates/ds_diploma_ru_kovalev_2025-9748-001.pdf) | [PDF](https://github.com/mk13inc/mk13inc/blob/main/certificates/ds_diploma_en_kovalev_2025-9748-001.pdf) |

## Pet проекты

Данные проекты были самостоятельно выполнены с целью закрепления и углубления знаний по различным темам Data Science.

| Название проекта | Описание | Используемые библиотеки | Файлы |
| :--------------- | :------- | :---------------------- | ----- |
| [Бинарная классификация изображений (Chest X-Ray Images)](nn_image_binary_clf) | На примере датасета Chest X-Ray Images решается задача бинарной классификации изображений. Решение строится на базе модели MobileNetV2. Изучаются факторы оказывающие влияние на повышение точности модели. Строятся тепловые карты активации класса модели с помощью Grad-CAM. | *pandas*, *numpy*, *matplotlib*, *PIL*, *tensorflow*, *keras* | [IPYNB](nn_image_binary_clf/project-study.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/pet-projects/blob/main/nn_image_binary_clf/project-report.ipynb) |

## Учебные проекты

Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме на курсах "Инструменты анализа данных" и "Специалист по Data Science".

| Название проекта | Описание | Используемые библиотеки | Файлы |
| :--------------- | :------- | :---------------------- | ----- |
| [Музыка больших городов](01_big_cities_music) | На реальных данных Яндекс Музыки проверяются гипотезы и сравнивается поведение пользователей двух столиц | *pandas* | [IPYNB](01_big_cities_music/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/01_big_cities_music/project.ipynb) |
| [Исследование надёжности заёмщиков](02_borrower_reliability_research) | На основе статистики о платёжеспособности клиентов, предоставленной кредитным отделом банка, определить показатели влияющие на факт погашения кредита в срок. | *pandas*, *seaborn* | [IPYNB](02_borrower_reliability_research/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/02_borrower_reliability_research/project.ipynb) |
| [Исследование объявлений о продаже квартир](03_apartments_listing_research) | На основе анализа данных о характеристиках квартир найти интересные особенности и зависимости, которые существуют на рынке недвижимости. | *pandas*, *matplotlib* | [IPYNB](03_apartments_listing_research/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/03_apartments_listing_research/project.ipynb) |
| [Исследование рынка компьютерных игр](04_video_games_market_research) | На основе данных из открытых источников о рынке видеоигр проводится анализ и находятся закономерности, определяющие успешность компьютерной игры. | *pandas*, *matplotlib* | [IPYNB](04_video_games_market_research/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/04_video_games_market_research/project.ipynb) |
| [Рекомендация тарифов](05_ml_tariff_recommendation) | На основе данных, содержащих информацию об активности клиентов оператора мобильной связи за месяц, строится прототип модели для подбора подходящего тарифа. Задача классификации, метрика качества: accuracy. | *pandas*, *matplotlib*, *scikit-learn* | [IPYNB](05_ml_tariff_recommendation/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/05_ml_tariff_recommendation/project.ipynb) |
| [Исследование истории TED-конфренций](06_ted_history_analysis) | На основе данных, собранных с сайта ted.com проводится анализ истории TED-конфренций. Результат представлен в виде презентации, включающей три дашборда:<br>• «История выступлений»;<br>• «Тематики выступлений»;<br>• «Авторы выступлений» | Tableau Public | [TWBX](06_ted_history_analysis/project.ipynb)<br>[WEB](https://public.tableau.com/app/profile/mk13inc/viz/Book3_17298697006630/Tableau) |
| [Прогнозные модели восстановления золота из руды](07_ml_gold_mining_analysis) | На основе данных, характеризующих технологический процесс, строится прототип модели машинного обучения для предсказания коэффициента восстановления золота из золотосодержащей руды. Задача регрессии с двумя целевыми признаками, итоговая метрика качества - sMAPE, которая определяется как 25% × sMAPE(target_1) + 75% × sMAPE(target_2). | *pandas*, *matplotlib*, *scikit-learn* | [IPYNB](07_ml_gold_mining_analysis/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/07_ml_gold_mining_analysis/project.ipynb) |
| [Прогнозные модели для отбора бурёнок](08_ml_cow_selection) | На основе данных предоставленных фермером, содержащих информацию о стаде коров на текущий момент, решаются две задачи:<br>1. Построить модель, для прогноза возможного удоя коровы. Задача регрессии, метрика качества: R²<br>2. Построить модель, которая будет рассчитывать вероятность получить вкусное молоко от коровы. Задача классификации, метрики качества: accuracy, recall, precision, confusion_matrix. | *pandas*, *matplotlib*, *numpy*, *phik*, *scikit-learn* | [IPYNB](08_ml_cow_selection/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/08_ml_cow_selection/project.ipynb) |
| [Прогнозные модели снижения покупательской активности интернет-магазина](09_ml_customer_activity_analysis) | На основе данных об активности клиентов и их взаимодействии с компанией решаются две задачи:<br>1. Построение модели, для предсказания вероятности снижения покупательской активности клиента в следующие три месяца. Задача классификации, метрика качества: ROC-AUC.<br>2. Выделение сегмента покупателей и разработки для них персонализированных предложений. | *pandas*, *matplotlib*, *numpy*, *phik*, *scikit-learn*, *shap* | [IPYNB](09_ml_customer_activity_analysis/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/09_ml_customer_activity_analysis/project.ipynb) |
| [HR-аналитика: Прогнозные модели уровня удовлетворённости и текучести кадров](10_ml_hr_analytics) | На основе данных содержащих информацию с характеристиками сотрудников компании, строятся две модели:<br>1. Для предсказания уровня удовлетворённости сотрудника на основе данных заказчика. Задача регрессии, метрика качества: SMAPE.<br>2. Для предсказания того, что сотрудник уволится из компании. Задача классификации, метрика качества: ROC-AUC. | *pandas*, *matplotlib*, *numpy*, *phik*, *scikit-learn*, *shap* | [IPYNB](10_ml_hr_analytics/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/10_ml_hr_analytics/project.ipynb) |
| [Выбор локации для скважины на основе прогнозной модели](11_ml_well_location) | На основе данных предоставленных добывающей компанией, содержащих информацию о пробах нефти в трёх регионах определяется регион с максимальной суммарной прибылью отобранных скважин на основе прогнозных значений модели. Анализ возможной прибыли и рисков осуществляется техникой *Bootstrap*. Задача регрессии, метрика качества: RMSE | *pandas*, *matplotlib*, *numpy*, *phik*, *scikit-learn* | [IPYNB](11_ml_well_location/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/11_ml_well_location/project.ipynb) |
| [Прогнозные модели для определения стоимости автомобилей](12_ml_car_price) | На основе данных предоставленных сервисом по продаже автомобилей с пробегом, содержащих информацию о технических характеристиках, комплектации и ценах исследуются прогнозные модели для определения рыночной их стоимости. Задача регрессии, метрика качества: RMSE | *pandas*, *matplotlib*, *numpy*, *phik*, *scikit-learn*, *lightgbm* | [IPYNB](12_ml_car_price/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/12_ml_car_price/project.ipynb) |
| [Прогнозирование заказов такси](13_ml_taxi_order_forecasting) | На основе хронологических данных о заказах такси в аэропортах исследуются прогнозные модели для определения загруженности такси на следующий час. Задача регрессии, метрика качества: RMSE | *pandas*, *matplotlib*, *numpy*, *statsmodels*, *scikit-learn*, *catboost*, *lightgbm* | [IPYNB](13_ml_taxi_order_forecasting/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/13_ml_taxi_order_forecasting/project.ipynb) |
| [Модели машинного обучения для классификации тональности текста](14_ml_text_sentiment_classification) | На основе датасета содержащего текст и токсичность комментария исследуются модели машинного обучения для классификации тональности текста. Задача классификации, метрика качества: F1. | *pandas*, *matplotlib*, *numpy*, *spacy*, *scikit-learn*, *torch*, *transformers* | [IPYNB](14_ml_text_sentiment_classification/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/14_ml_text_sentiment_classification/project.ipynb) |
| [Определение возраста покупателей](15_nn_face_age_predictor) | На основе общедоступного датасета изображений строится модель нейронной сети для предсказания приблизительного возраста покупателей. Задача регрессии, метрика качества: MAE | *pandas*, *matplotlib*, *tensorflow*, *keras* | [IPYNB](15_nn_face_age_predictor/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/15_nn_face_age_predictor/project.ipynb) |
| [Прогнозные модели температуры сплава](16_steel_temp_ml_analysis) | На основе набора признаков, характеризующих технологический процесс, исследуются модели для определения конечной температуры стального сплава. Задача регрессии, метрика качества: MAE | *pandas*, *matplotlib*, *phik*, *scikit-learn*, *catboost*, *shap* | [IPYNB](16_ml_steel_temp_analysis/project.ipynb)<br>[HTML](https://nbviewer.org/github/mk13inc/yandex_practicum_projects/blob/main/16_ml_steel_temp_analysis/project.ipynb) |
