## Создать таблицы и задать связи, заполнить данными для следующих примеров:

### 1. Статьи и комментарии:
 - статья может иметь несколько комментариев
 - комментарий может принадлежать только одной статьемассивы
 - статья - название, текст, дата публикации
 - комментарий - текст, количество лайков

### 2. Книги и отзывы:
- книга может иметь несколько отзывов
- отзыв может принадлежать только одной книге
- книга - название, жанр, год издания
- отзыв - текст, оценка

### 3. Курсы и отзывы:
- курс может иметь несколько отзывов
- отзыв может принадлежать только одному курсу
- курс - название, описание
- отзыв - текст, оценка

## Для каждого примера сделать вывод связанных сущностей (за один запрос)
- зависимая сущность должна быть представлена в виде массива объектов
- учесть случай когда на главную таблицу может не быть ссылок в строках зависимой таблицы
- если на строки из главной таблицы нет ссылок из зависимой таблицы, эти строки всё равно должны выводиться
- на одну из строк главной таблицы должно быть хотя бы 2 ссылки из зависимой таблицы