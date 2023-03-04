Установка зависимостей:

`pip install -r requirements.txt`

Проверка линтером:

`black src`

Проверка тестов:

`python -m doctest --option ELLIPSIS src/model.py`

Проверка типизации:

`mypy --strict --show-error-codes src`