# Описание предметных областей

|  № | Предметная область          | Основные сущности (пример массива объектов)            | Типовые операции в ЛР                    |
| -: | --------------------------- | ------------------------------------------------------ | ---------------------------------------- |
|  1 | Интернет-магазин косметики  | `products` (id, title, price, category, stock, status) | фильтр по категории, расчёт суммы, CRUD  |
|  2 | Каталог онлайн-курсов (LMS) | `courses` (id, title, duration, level, status)         | фильтр по уровню, поиск, статистика      |
|  3 | ServiceDesk (заявки)        | `tickets` (id, title, priority, status, createdAt)     | смена статуса, фильтр, подсчёт open      |
|  4 | Учёт сотрудников            | `employees` (id, name, position, salary, active)       | фильтр, расчёт фонда оплаты труда        |
|  5 | Каталог фильмов             | `movies` (id, title, year, rating, genre)              | сортировка по рейтингу, фильтр по жанру  |
|  6 | Библиотечный каталог        | `books` (id, title, author, year, available)           | фильтр по наличию, подсчёт по автору     |
|  7 | Бронирование переговорных   | `rooms` (id, name, capacity, status, date)             | фильтр по дате, подсчёт занятых          |
|  8 | CRM-клиенты                 | `clients` (id, name, email, totalOrders, status)       | поиск, сортировка по обороту             |
|  9 | Портал вакансий             | `vacancies` (id, title, salary, location, active)      | фильтр по городу, средняя зарплата       |
| 10 | Task Manager                | `tasks` (id, title, priority, status, deadline)        | фильтр, сортировка по сроку              |
| 11 | Аренда автомобилей          | `cars` (id, model, pricePerDay, available)             | фильтр, расчёт стоимости                 |
| 12 | Онлайн-дневник оценок       | `grades` (id, subject, score, date)                    | средний балл, фильтр по предмету         |
| 13 | Складской учёт              | `inventory` (id, title, quantity, minLevel)            | дефицитные позиции, суммарное количество |
| 14 | Каталог музыкальных треков  | `tracks` (id, artist, title, duration, genre)          | суммарная длительность, фильтр           |
| 15 | Онлайн-запись к врачу       | `appointments` (id, patient, doctor, date, status)     | фильтр по врачу, подсчёт записей         |
| 16 | Туристические туры          | `tours` (id, country, price, duration, available)      | средняя цена, фильтр по стране           |
| 17 | Платформа вебинаров         | `webinars` (id, title, speaker, date, status)          | фильтр по дате, подсчёт upcoming         |
| 18 | Доставка еды                | `orders` (id, client, total, status)                   | фильтр по статусу, сумма заказов         |
| 19 | Каталог гаджетов            | `devices` (id, brand, model, price, stock)             | сортировка по цене, поиск                |
| 20 | SaaS-подписки               | `subscriptions` (id, user, plan, price, active)        | активные подписки, выручка               |
| 21 | Онлайн-экзамены             | `tests` (id, subject, attempts, passed)                | процент успешных, фильтр                 |
| 22 | Фитнес-трекер               | `workouts` (id, type, duration, calories, date)        | суммарные калории, фильтр                |
| 23 | Учёт проектов               | `projects` (id, name, budget, status)                  | бюджет активных проектов                 |
| 24 | Аренда жилья                | `apartments` (id, city, price, rooms, available)       | фильтр по городу, сортировка             |
| 25 | Магазин книг                | `products` (id, title, genre, price, stock)            | фильтр по жанру, поиск                   |
| 26 | Платформа стартапов         | `startups` (id, name, investment, stage, active)       | фильтр по стадии, сумма инвестиций       |
| 27 | Производственные заказы     | `manufacturingOrders` (id, product, quantity, status)  | объём производства, фильтр               |
| 28 | Сервис отзывов              | `reviews` (id, user, rating, comment, date)            | средний рейтинг, фильтр                  |
| 29 | Каталог мероприятий         | `events` (id, title, date, location, ticketsLeft)      | фильтр по дате, доступные билеты         |
| 30 | Учёт расходов               | `expenses` (id, category, amount, date)                | сумма расходов, фильтр по категории      |
