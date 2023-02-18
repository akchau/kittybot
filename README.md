[Перейти к остальным проектам](https://github.com/akchau/akchau/blob/main/README.md#проекты)

# kittybot
###### Телеграмм бот, который умеет отправлять фото котиков и собачек, быть секретарем и даже поддержать диалог.

### Функции:
- Получение с внешнего API фото рандомного кота/собаки
- Узнавать время
- Сообщать погоду
- Отвечает на приветствия, прощания и говорит как дела и чем он занимается

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram.git
```

```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```
Далее необходимо создать файл `.env` в корневой папке. И добавить в него своЙ TOKKEN. Пример в файле `.env_example`.
Токен можно получить в телеграмм @BotFather:
`/start
/newbot`

Файл Procfile указывает стартовый файл при хостинге.
