# Классификация комментариев

## Задача

Нужно построить модель, которая классифицирует комментарии к товарам на позитивные и негативные. <br>
Необходимо достичь значения метрики F1 ≥ 0.75

## Инструменты

Задача решена с применением TF-IDF реализованной в *Scikit-learn*

Используемые библиотеки:
- pandas
- numpy
- Nltk
- Scikit-learn
- CatBoost

## Выводы

Из текста были удалены стоп-слова, и произведена векторизация (расчёт TF-IDF). С применением CatBoost получилось достичь метркика F1 = 0.7597

## Данные

Набор комментариев с метками токсичности.