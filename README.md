решения задач, приближенных к задачам реального бизнеса:
• написание различных SQL-запросов (MS SQL, MySQL, PosgreSQL) для извлечения необходимых данных для аналитики:
Select со всеми его возможностями…
Объединение данных из различных таблиц, в т.ч. Join
Применение оконных функций при количества…
Построение таблицы продаж товаров
Решение бизнес-кейсов на языке Python
Аналитика активности пользователей платформы
Создала дашборд в PowerBI (подключила базу данных ____ к PowerBI, написала SQL—запросы для построения визуализаций, собрала дашборд «Анализ…, сформулировала гипотезы и провела их тестирование, результаты тестирования»
ТЗ
спецификации

https://github.com/sashinayub/ed-projects/blob/4bd2506801a3734d1ceba07a7ad2d2ec5393453f/python

<img width="958" height="667" alt="image" src="https://github.com/user-attachments/assets/349a5060-7fa4-45f7-a649-b8141e1f20c9" />
Fast Transformer Twitter
PyPI Run Tests Upload Python Package Code style: black Open In Colab

DOI GitHub License GitHub stars GitHub followers Twitter Follow

This repo implements Fastformer: Additive Attention Can Be All You Need by Wu et al. in TensorFlow. Fast Transformer is a Transformer variant based on additive attention that can handle long sequences efficiently with linear complexity. Fastformer is much more efficient than many existing Transformer models and can meanwhile achieve comparable or even better long text modeling performance.



Installation
PyPI
Run the following to install:

pip install fast-transformer
Docker
To install the package using Docker run the following:

docker pull ghcr.io/rishit-dagli/fast-transformer:0.2.0
Developing fast-transformer
To install fast-transformer, along with tools you need to develop and test, run the following in your virtualenv:

git clone https://github.com/Rishit-dagli/Fast-Transformer.git
# or clone your own fork

cd fast-transformer
pip install -e .[dev]
To run rank and shape tests run any of the following:

python -m fast_transformer.test_fast_transformer
pytest fast_transformer --verbose
Usage
