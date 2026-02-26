# OTUS. Cookiecutter Simple Template

Шаблон проекта для быстрого создания Python-приложений с использованием Cookiecutter.

## Описание

Этот шаблон предоставляет базовую структуру проекта. 
Включает в себя настройку окружения разработки, 
базовые зависимости для работы с данными (pandas, numpy, scikit-learn), 
инструменты для тестирования и линтинга, а также Jupyter notebook для исследований.

## Установка

0. Склонируйте проект

```bash
git clone git@github.com:NickOsipov/otus-cookiecutter-simple-template.git
```

1. Установите библиотеку `cookiecutter` в виртуальном окружении:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2. Создайте проект:
```bash
# сначала перейдите в нужную директорию
cookiecutter https://github.com/NickOsipov/otus-cookiecutter-simple-template
```

## Лицензия

MIT

## Автор

[Nick Osipov](https://t.me/NickOsipov)

## Контакты

Если у вас есть вопросы или предложения, пожалуйста, свяжитесь со мной через Telegram или создайте issue в репозитории.
