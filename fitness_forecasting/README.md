﻿# Проверка гипотез по увеличению выручки в интернет-магазине. Оценка результатов А/В теста.

## Задача: 
- на основе данных о посетителях сети фитнес-центров спрогнозировать вероятность оттока для каждого клиента в следующем месяце
- сформировать с помощью кластеризации портреты пользователей;

## План анализа:
* Импорт и предобработка данных;
* Исследовательский анализ данных;
* Строим модель оттока:
  - методом линейной регрессии;
  - методом "случайного леса"
  - сравниваем метрики: доля правильных ответов, полнота, точность;
  - выбираем лучшую модель;
* Кластеризация клиентов:
  - на основе дендрограммы определяем число классов;
  - проводим кластеризацию методом K-means;
  - анализируем признаки внутри кластеров;
  - формируем портрет клиентов разных кластеров;
* Выводы и дальнейшие рекомендации бизнесу.
