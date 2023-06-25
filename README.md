# Разработка приложения для ведения блога

## Цель: Разработать приложение Django для ведения блога

### Задачи:

1. Создайте базовый проект на Django. Оно должно включать модели для блога, которые будут содержать такую информацию как: заголовок, слаг, имя автора, текст, дата и время создания, дата и время публикации, дата и время редактирования и статус поста.

2. ДАЛЕЕ ЕЩЕ


## Установка и запуск:

#### Клонируйте репозиторий

```bash
git clone https://github.com/nurai5/blog_app_a_mele
cd  codify-assignment-python
```

#### Активируйте виртуальное окружение

```bash
python3 -m venv .venv && . .venv/bin/activate 
pip install -r requirements.txt
```

#### Запустите миграции

```bash 
python3 manage.py makemigratons
python3 manage.py migrate
```

#### Запустите сервер

```bash
python3 manage.py runserver
```
