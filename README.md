# Хакатон 2022
**Проект сделан во время участия в Хакатоне 2022**

Написан на Python с использованием библиотеки Flask как основной

Реализованный функционал:
- Фронт система 
- Бэк система 
- Модуль народного голосования

Участники:
- Мельников Сергей
- Жуков Олег
- Попов Виктор
- Чумейко Влад
- Шиянов Никита


# Как поменять новости
На нашем сайте есть встроенная система новостей для того чтобы изменить новости достаточно изменить содержание файла ```news.hml```

Изменять необходимо внутри блока ```<div class="panel_news" >```

Чтобы не нарушить оформление сайта

В самом файле есть коментарии в таком виде -> ```{# коментарий #}```

Они подскажут какой блок за какую новость отвечает
# Как запустить
- Необходимо загрузить все библиотеки из requirements.txt
- Для запуска на lockalhost запустить файл main.py

- Для запуска запуска хоста необходимо заменить ip адресс и port в функции main файла main.py

И запускать сайт через эту строчку (Необходимо раскоментировать):

```app.run(host='0.0.0.0', port=port)```

**Изначально:**
Логин админского пользователя: admin@mail.ru

Пароль: admin

Управление сайтом происходит через Администратора 
- Смена этапа конкурса 
- Добавление проверяющих экспертов

Все эти действия можно сделать из панели управления сразу на сайте на главной странице:

![image](https://user-images.githubusercontent.com/91543105/205495482-67634044-e1d2-4a21-8a99-5e78526c315e.png)
# Этапы конкурса
**Ожидается запуск**

Недоступно:
- Создание заявок
- Таблица работ учасников

Доступно:
- Регистрация пользователей

**Прием заявок**

Недоступно:
- Таблица работ учасников

Доступно:
- Создание заявок
- Регистрация пользователей

**Независимая экспертиза**

Недоступно:
- Создание заявок

Доступно:
- Народное голосование
- Таблица работ учасников
- Регистрация пользователей

**Завершение конкурса**

Недоступно:
- Создание заявок
- Народное голосование

Доступно:
- Таблица работ учасников (Всем виден протокол оцениивания экспертов любой работы и количество голосов у работы)
- Регистрация пользователей
