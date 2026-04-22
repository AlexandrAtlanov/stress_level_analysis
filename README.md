# Проект по анализу уровня стресса

Классификация уровня стресса (низкий/средний/высокий) опрошенных людей на основе данных об их сне, экранном времени и физической активности.

## Стек

Python, pandas, scikit-learn, matplotlib, seaborn, CatBoost

## Данные 

Источник: Kaggle - Sleep, Screen Time and Stress Analysis (Прямая ссылка - https://www.kaggle.com/datasets/jayjoshi37/sleep-screen-time-and-stress-analysis/code)

## Задача

Проанализировать данные, имеющие дисбаланс классов. Использовать методы многоклассовой классификации.

## Запуск 

Открыть файл stress_analysis.ipynb в Jupyter Notebook.

## Результаты моделей на основе имеющихся данных

1) Логистическая регрессия: 
* ROC-AUC: 0.978
* F1 Weighted: 0.889

2) Случайный лес:
* ROC-AUC: 0.976
* F1 Weighted: 0.889

3) CatBoost:
* ROC-AUC: 0.976
* F1 Weighted: 0.888

## Финальная модель

Финальной моделью была выбрана логистическая регрессия с стандартными параметрами.
