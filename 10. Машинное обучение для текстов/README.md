## Классификация комментариев в интернет-магазине

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 
**Задача:** Обучить модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок.

 
## Библиотеки

`pandas`
`numpy`
`matplotlib`
`time`
`nltk`
`sklearn`
`statsmodels`
`lightgbm`



##  Модели

- Логистическая регрессия
- LinearSVC
- DummyClassifier



## Итоги:

- Проведена обработка и исследовательский анализ данных
- Проведена очистка текста от лишних знаков и лемматизация
- Проведена векторизация признаков
- Обучены модели "Логистическая регрессия", "LinearSVC" и "DummyClassifier" с использованием GridSearchCV
- Рассчитаны метрики F1 для всех моделей
- Проведена проверка лучшей модели на тестовой выборке
