# Виртуальные окружения
- https://github.com/pyenv/pyenv - управляем питонами
- venv - из коробки
- virtualenv - https://virtualenv.pypa.io/en/latest/index.html
- https://github.com/pypa официальные инструменты для управления зависимостями
- pipenv - объединяем virtualenv и pip

# Poetry
- https://python-poetry.org/
- pyproject.toml https://peps.python.org/pep-0621/

venv
1. Установить виртуальное окружение venv: python - m venv venv
2. Активировать виртуальное окружение: .\venv\Scripts\activate
3. Установить pytest: pip install pytest
4. Зафиксировать зависимости: pip freeze
5. Записать зависимости в файл requirements.txt: pip freeze > requirements.txt

pipenv
- Установить pipenv: pip install pipenv
- Установить pytest: pipenv install pytest
- Активировать окружение: pipenv shell

poetry
