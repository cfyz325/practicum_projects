На основе данных из банка определить клиент, который может уйти

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Для выполнения поставленной задачи были использованы следующие инструменты и методы:
- модели DecisionTreeClassifier, RandomForestClassifier, LogisticRegression
- Matplotlib
- Pandas
- библиотека Scikit-learn
- методы кодирования OHE и OrdinalEncoder

Лучшей моделью с лучшими гиперпараметрами оказалась модель "Случайный лес".