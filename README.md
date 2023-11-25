
# Лабораторна Робота: Автоматичне Укладання Частотних Словників

Цей репозиторій містить коди для лабораторної роботи з автоматичного укладання частотних словників на основі двох різних текстових вибірок.

## Опис
Проект включає три основних скрипти Python, які використовуються для екстракції тексту з PDF-файлів, токенізації, морфологічного аналізу словоформ, а також для створення та управління базами даних SQLite з частотними словниками.

### Файл 1: `funcs.py`
Цей файл включає функції для екстракції тексту з PDF-документів, його очищення та підготовки до обробки, а також для парсингу словоформ.

### Файл 2: `main.py`
Головний скрипт, що займається обробкою тексту, його токенізацією, морфологічним аналізом, а також створенням частотних словників і записом даних в базу даних SQLite.

### Файл 3: `sql_lib.py`
Модуль для роботи з базою даних SQLite, включаючи функції створення таблиць, вставки даних та інші операції з базою даних.

## Залежності
- PyPDF2
- re (стандартний модуль Python для регулярних виразів)
- tokenize_uk
- pymorphy3
- sqlite3 (стандартний модуль Python для роботи з SQLite)
- json (стандартний модуль Python для роботи з JSON файлами)

## Інструкція з використання
1. Встановіть необхідні залежності.
2. Запустіть файл `main.py` з вказанням шляху до текстового файлу або PDF-документу.
3. Перевірте результати в базі даних SQLite.



