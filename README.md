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

# Fast Transformer [![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2FRishit-dagli%2FFast-Transformer)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FRishit-dagli%2FFast-Transformer)

![PyPI](https://img.shields.io/pypi/v/fast-transformer)
[![Run Tests](https://github.com/Rishit-dagli/Fast-Transformer/actions/workflows/tests.yml/badge.svg)](https://github.com/Rishit-dagli/Fast-Transformer/actions/workflows/tests.yml)
[![Upload Python Package](https://github.com/Rishit-dagli/Fast-Transformer/actions/workflows/python-publish.yml/badge.svg)](https://github.com/Rishit-dagli/Fast-Transformer/actions/workflows/python-publish.yml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rishit-dagli/Fast-Transformer/blob/main/example/fast-transformer-example.ipynb)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5406025.svg)](https://doi.org/10.5281/zenodo.5406025)
![GitHub License](https://img.shields.io/github/license/Rishit-dagli/Fast-Transformer)
[![GitHub stars](https://img.shields.io/github/stars/Rishit-dagli/Fast-Transformer?style=social)](https://github.com/Rishit-dagli/Fast-Transformer/stargazers)
[![GitHub followers](https://img.shields.io/github/followers/Rishit-dagli?label=Follow&style=social)](https://github.com/Rishit-dagli)
[![Twitter Follow](https://img.shields.io/twitter/follow/rishit_dagli?style=social)](https://twitter.com/intent/follow?screen_name=rishit_dagli)

This repo implements [Fastformer: Additive Attention Can Be All You Need](https://arxiv.org/abs/2108.09084) by Wu et al. in 
TensorFlow. **Fast Transformer** is a Transformer variant based on additive attention that can handle long sequences 
efficiently with linear complexity. Fastformer is much more efficient than many existing Transformer models and can 
meanwhile achieve comparable or even better long text modeling performance.

![](https://github.com/Rishit-dagli/Fast-Transformer/blob/main/media/architecture.png)

## Installation

### PyPI

Run the following to install:

```sh
pip install fast-transformer
```

### Docker

To install the package using Docker run the following:

```sh
docker pull ghcr.io/rishit-dagli/fast-transformer:0.2.0





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
