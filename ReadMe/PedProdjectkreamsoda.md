# Педпроект Агрегатор Фильмов

## Задача 1.1

### Гость:

1. Ограниченный доступ.
2. Возможность просмотра общей информации.
3. Возможность поиска фильмов по названию.

### Пользователь:

1. Стандартный доступ.
2. Возможность просмотра общей информации.
3. Возможность поиска фильмов по названию. (Так же как и гость)
4. Возможность создание своего списка просмотров.
5. Возможность оставления комментариев.
6. Возможность выставления оценок.
7. (*) Возможность оставления запросов на добавление нового контента. В текстовом виде. Запрос будет отображаться только у администраторов.
8. (*) Возможность оставлять информацию о ошибках. В текстовом виде. Запрос будет отображаться только у администраторов.

### Администратор:

1.Отдельной системой. С возможностью отслеживания изменений.
2. Возможностью добавления новых данных и изменения старых.


## Задача 1.2

### 1. Фильм:
Название.
ID (ключ).
Год выпуска.
Продолжительность.
Жанры.
Страна производства.
Описание.
Изображение.

### 2. Актёр:
Имя.
Фамилия.
ID (ключ).
Год рождения.
Страна рождения.

### 3. Режиссёр:
Имя.
Фамилия.
ID (ключ).
Год рождения.
Страна рождения.

### 4. Оценка.
Дата оставления оценки.
Имеет значение от 0 до 10.


### 5. Коментарий.
Дата оставления коментария.
Имеет поле для ввода текста.
Имеет автора (пользователя)

### 6. Системное сообщение. (Запрос на добавление, сообщение об ошибке)
Дата обращения.
Поле для ввода текста.

### 7. Поиск.
Поле для ввода текста. 
Во всех местах где пользователь вводит данные дожна быть волидация.

### 8. Пользователь.
Id
Логин
Хэш пароля.  
mail
Имеет счётчик времени, проведённого на сайте. --(для чего тебе этот счётчик?) 
Просто чтоб иметь информацию по времени посещения и удержания сайта. Понятно что это пед проэкт но условно чтоб передавать инфу потенциальным рекламодателям к примеру.


### 9. Администратор.
Отдельный интерфейс не связанный програмно с основным.
id
mail
Логин 
Хэш пароля.     
Доступ к 11му пункту.

## Задача 2

Язык программирования бэк C# «Ну тут просто по тому что другие я не знаю»
Фронт HTML «Ну тут я вообще никакой не знаю этот просто вроде бы самый простой.
ASP.NET Core фреймворк основной. Да и думаю в дальнейшем имея бэк ни что не помешает переписать.»  
по шаблону MVC. Для работы с БД используя entity framework.
В качестве базы данных использовать MsSQL «PostgreSQL наверное лучше но она сложнее поэтому пока наверное нет».
Без Docker по тому что пока его не знаю.
Да и в дальнейшем когда будет уже что то готово будет интересно потом попробовать его уже поверх готового проекта
поставить посмотреть как это реализуется.
