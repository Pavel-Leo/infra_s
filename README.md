# Infra_sprint1

## Описание
Проект Infra_sprint1 содержит приложение Kittygram — социальная сеть для обмена фотографиями любимых питомцев. 
Это полностью рабочий проект, который состоит из бэкенд-приложения на Django и фронтенд-приложения на React.

После регистрации пользователь может просматривать уже опубликованные фогорафии котиков, а так же публиковать своих, после чего свои пбликации можно редактировать и удалять.


## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Pavel-Leo/infra_sprint1.git
```

```
cd infra_sprint1/backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv (для mac и linux)
python -m venv venv (для windows)
```

```
source venv/bin/activate (для mac и linux)
source venv/Scripts/activate (для windows)
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip (для mac и linux)
python -m pip install --upgrade pip (для windows)
```

```
перейти в дирректорию где хранится файл requirements.txt и оттуда выполнить команду:

pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate (для mac и linux)
python manage.py migrate (для windows)
```

Запустить проект:

```
перейти в дирректорию где хранится файл manage.py и оттуда выполнить команду:

python3 manage.py runserver (для mac и linux)
python manage.py runserver (для windows)
```

