## Домашнее задание к занятию «Работа с данными (DDL/DML)» - Шаров Олег

---

## Задание 1

### 1.3. Список пользователей
Скриншот:  
![Список пользователей](img/task1_3_users.png)

### 1.5. Права пользователя sys_temp
Скриншот:  
![Права sys_temp](img/task1_5_grants.png)

### 1.8. Список таблиц базы sakila
Скриншот:  
![Таблицы sakila](img/task1_8_tables.png)

---

## Задание 2

Таблица соответствия названий таблиц и их первичных ключей:

| Название таблицы | Название первичного ключа |
|------------------|---------------------------|
| actor            | actor_id                  |
| address          | address_id                |
| category         | category_id               |
| city             | city_id                   |
| country          | country_id                |
| customer         | customer_id               |
| film             | film_id                   |
| film_actor       | actor_id                  |
| film_actor       | film_id                   |
| film_category    | film_id                   |
| film_category    | category_id               |
| film_text        | film_id                   |
| inventory        | inventory_id              |
| language         | language_id               |
| payment          | payment_id                |
| rental           | rental_id                 |
| staff            | staff_id                  |
| store            | store_id                  |

Скриншот результата SQL-запроса:

![Первичные ключи таблиц](img/task2_primary_keys.png)

---

## Выводы

1. Установлен и настроен контейнер MySQL 8.0 через Docker.
2. Создан пользователь `sys_temp` с полными правами (`ALL PRIVILEGES`).
3. Успешно восстановлен учебный дамп базы данных `sakila`.
4. Получен список всех таблиц базы и их первичных ключей с помощью запроса к `information_schema`.

