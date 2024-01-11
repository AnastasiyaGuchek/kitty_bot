# KittyBot

Телеграм-бот c API сайта с фотографиями котов. По кнопке /newcat пользователь получает в чат рандомное изображение с котом из интернета.


### Технологии:
- Python 3.9
- python-dotenv 0.21.1
- python-telegram-bot 13.7

### Установка и запуск

**Клонируйте репозиторий:**

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:AnastasiyaGuchek/kitty_bot.git
```

```
cd kitty_bot
```

**Установите и активируйте виртуальное окружение:**

```
python -m venv venv
```

* Если у вас Linux/macOS

    ```
    source venv/bin/activate
    ```

* Если у вас Windows

    ```
    source venv/scripts/activate
    ```

**Обновите менеджер pip и установите зависимости**

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

### Необходимо заполнить env-файл для запуска

- токен телеграм-бота, полученный от @BotFather

```
touch .env
```

```
TELEGRAM_TOKEN = '...'
```

### Запуск проекта:

**Локально:**
```
python kittybot.py
```
