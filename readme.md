Кабинет админа: 
форма создания категории(название, описание, картинка)
форма создания новости(Заголовок, описание, текст, картинка, дата, имя автора, категория, статус)
Админ видит список категорий и список новостей с возможностью их редактирования



Сам блог:
Страница категорий
Страница новостей по категории
Страница новости
Первая страница - категории, при переходе на категорию открываются все новости по ней, при переходе на новость открывается страница новости
Внизу страницы новости выводить счетчик - количество просмотров и количество уникальных посетителей(один уникальный посетитель может сделать несколько просмотров), хранить в Redis

Использовать миграции для создания БД
Использовать стандартный компонент авторизации и регистрации для входа в админ часть
Использовать таблицы для вывода информации
