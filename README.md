# Kaggle Titanic - Gradient Boosting Classifier

Решение классической задачи бинарной классификации (предсказание выживаемости пассажиров Титаника).

## Что реализовано:
*   **EDA (Разведочный анализ):** Анализ выживаемости в разрезе пола, класса, возраста и стоимости билета.
*   **Feature Engineering:** Создание новых признаков (возрастные группы, наличие семьи) и кодирование категориальных переменных (One-Hot Encoding).
*   **Обработка пропусков:** Заполнение пропусков в возрасте медианными значениями с учетом пола и класса пассажира.
*   **Моделирование:** Обучение модели градиентного бустинга (`GradientBoostingClassifier`).
*   **Оценка качества:** Расчет метрик Accuracy, Precision, Recall и построение матрицы ошибок (Crosstab).

## Стек:
*   Python (Pandas, NumPy)
*   Scikit-learn (Gradient Boosting)
*   Seaborn, Matplotlib (визуализация)

## Как запустить:
1. Установите зависимости: `pip install pandas numpy scikit-learn seaborn matplotlib`
2. Откройте файл `.ipynb` в Jupyter Notebook или Google Colab.
