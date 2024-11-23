# Web_Flask_project
Этот проект представляет собой веб-приложение, разработанное с использованием фреймворка Flask (Python).

## Содержание
- [Описание](#описание)
- [Главная страница](#главная-страница-)
- [Страница со списком книг](#страница-со-списком-книг)
- [Страница с подробной информации о книге](#страница-с-подробной-информации-о-книге)
- [Установка репозитория](#установка-репозитория)

## Описание
Веб-приложение представляет собой онлайн-магазин электронных книг _'Bookland'_. Он включает в себя: 
- Главную страницу;
- Страницу со списком книг;
- Подробную информацию по каждой книге.

Сайт оптимизирован для мобильных устройств и настольных компьютеров.

### Главная страница 
Представляет собой информацию о всех книгах на сайте  - это небольшие окошки с изображением обложек, 
названия и цены. Отсюда есть ссылка страницу со списком книг под названием "Все книги"
![img.png](img_for_readme/img.png)

### Страница со списком книг

Представляет собой таблицу книг со следующими колонками: 
- Название книги;
- Автор; 
- Жанр; 
- Обложка; 
- Показать обложку.

Название книги является ссылкой на страницу с более подробной информацией о книге. 
Также есть поддержка пагинации страницы.
![img_1.png](img_for_readme/img_1.png)

### Страница с подробной информации о книге
Страница имеют всю основную информации о книге. 
Помимо названия, автора и жанра и обложки есть следующая информация: 
- Аннотация книги; 
- Регистрационный номер ISBN;
- Издательство;
- Год издания.

Есть возможность при нажатии на изображение обложки открыть в отдельном окне для детального просмотра.
![img_2.png](img_for_readme/img_3.png)

## Установка репозитория
1. Клонируйте репозиторий:
```bash
git clone https://github.com/SpektR632/Web_FLask_project.git
```
2. Откройте проект в предпочитаемом редакторе;
3. Установите зависимости из файла requirements.txt;
4. Перейдите в директорию проекта ```cd Website```;
5. Запустите локальный сервер для просмотра сайта. Пример запуска: 

```flask --app routes.py run```
