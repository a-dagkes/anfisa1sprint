# Анфиса для друзей

## О проекте

**Анфиса для друзей** - это ...

## Использованные технологии**:
* Django 3.2.3: фреймворк для создания веб-приложений

## Установка окружения

Клонировать репозиторий и перейти в него в командной строке:

```bash
git clone https://github.com/a-dagkes/ice_cream_catalog.git
```

```bash
cd ice_cream_catalog
```

Cоздать виртуальное окружение:

```bash
python3 -m venv env
```

Структура файлов станет такой:

```

ice_cream_catalog/
├── anfisa_for_friends/
├── html_templates/
├── env/   
├── .gitignore
├── LICENSE
├── requirements.txt
└── README.md
```

Активировать виртуальное окружение:

* Если у вас Linux/macOS

    ```bash
    source env/bin/activate
    ```

* Если у вас windows

    ```bash
    source env/scripts/activate
    ```

💡 Все дальнейшие команды в терминале надо выполнять с активированным виртуальным окружением.

Обновите pip:

```bash
python -m pip install --upgrade pip
```

### Установка зависимостей из файла *requirements.txt*:

```bash
pip install -r requirements.txt
```

### Применение миграций
    
В директории с файлом manage.py выполните команду: 

```bash
python manage.py migrate
```

### Запуск проекта в dev-режиме
    
В директории с файлом manage.py выполните команду: 

```bash
python manage.py runserver
```

В ответ Django сообщит, что сервер запущен и проект доступен по адресу [http://localhost/](http://localhost/). 
