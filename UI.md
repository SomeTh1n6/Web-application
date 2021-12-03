# Проектирование интерфейсов
### 1. Список элементов управления

* ### Гость (Неавторизованный пользователь)
    * Главная страница
    * Страница авторизации
    * Страница регистрации
    * Страница с товарами, удовлетворяющими условиям поиска
    * Страница конкретного товара

* ### Пользователь
    * Главная страница
    * Корзина
    * Страница с товарами, удовлетворяющими условиям поиска
    * Избранное
    * Страница конкретного товара
    * Оформление заказа
    * Настройка профиля (редактирование или внесение)
    * Страница возврата некачественного товара

* ### Администратор
    *  Все то, что есть у ***Пользователя***
    *  Список заказов с приложенной информацией о нем (1)
    *  Список заявок по возврату (2)
    *  Конкретный заказ
    *  Конкретная заявка на возврат
    *  Профиль администратора (имеет дополнительно (1) и (2))

### 2. Эскизы основных страниц сайта (прототип)
* ##### Главная страница
![image](https://user-images.githubusercontent.com/58702589/144573182-b08ac1fc-242a-470e-9266-f7bdec49cfbc.png)

* ##### Страница авторизации
![image](https://user-images.githubusercontent.com/58702589/144573208-a145a9dc-4f56-446d-a5ee-d21d28fd7f9b.png)

* ##### Страница регистрации
![image](https://user-images.githubusercontent.com/58702589/144573240-116c20a2-3b3a-4bb5-8102-48fe51969894.png)

* ##### Корзина
![image](https://user-images.githubusercontent.com/58702589/144573272-4b0e41a7-f6dc-46ca-9b64-76f64f5b0dd1.png)

![image](https://user-images.githubusercontent.com/58702589/144573310-c2e9cd33-67b3-44ff-a4a3-85aa0bffe0d9.png)

* ##### Страница с товарами, удовлетворяющими условиям поиска
![image](https://user-images.githubusercontent.com/58702589/144573350-7f5c3d78-b776-457f-b296-2286edf9d5aa.png)

![image](https://user-images.githubusercontent.com/58702589/144573383-2ec0f05a-6322-4be4-892e-ef6b6293c093.png)

* ##### Избранное
![image](https://user-images.githubusercontent.com/58702589/144573417-60219fee-d460-445e-a414-4536b1c13948.png)

![image](https://user-images.githubusercontent.com/58702589/144573450-5a527065-096b-4f04-810c-7747b1c6235d.png)

* ##### Страница конкретного товара
![image](https://user-images.githubusercontent.com/58702589/144573502-6ce17d15-43d1-4df9-9537-62aab4b04f3f.png)

* ##### Оформление заказа
![image](https://user-images.githubusercontent.com/58702589/144603881-d451ab86-2fd6-4cad-a7e5-58aad97430cb.png)

* ##### Профиль
![image](https://user-images.githubusercontent.com/58702589/144604754-85c217bd-e3cc-4c29-93ac-29f19b16a8b3.png)

* ##### Настройка профиля
![image](https://user-images.githubusercontent.com/58702589/144650310-5ba3426c-f1a7-499c-8e57-ff793a58ddc4.png)

* ##### Форма оставления отзыва
![image](https://user-images.githubusercontent.com/58702589/144653533-223a71af-eb0b-40f0-a4b8-258c2b7d2693.png)

* ##### Отзывы на странице с конкретным товаром
![image](https://user-images.githubusercontent.com/58702589/144653493-bee870fb-d705-469a-9385-ac0f7fdfac9a.png)

* ##### Страница возврата некачественного возврата
![image](https://user-images.githubusercontent.com/58702589/144604192-65da0dc2-bb04-4a08-9e26-cdad2b6e91fa.png)

* ##### Список заказов (Заявки конкретного **Пользователя**)
![image](https://user-images.githubusercontent.com/58702589/144653891-1482023a-15aa-4170-ad95-7f8273401d1b.png)

* ##### Список заявок по возврату (Заявки конкретного **Пользователя**)
![image](https://user-images.githubusercontent.com/58702589/144654358-1502befc-2af7-473c-bb9d-a9dc8ad9f1b2.png)

* ##### Конкретный заказ вид **Пользователя**
![image](https://user-images.githubusercontent.com/58702589/144654293-bba9ccea-4a16-4ec5-a885-00be24b25028.png)

* ##### Конкретная заявка на возврат вид **Пользователя**
![image](https://user-images.githubusercontent.com/58702589/144607215-8945e141-5e3b-459b-a42a-28b59c43b5f3.png)

* ##### Профиль администратора (имеет дополнительно (1) и (2))

* ##### Список заказов **Пользователей**
![image](https://user-images.githubusercontent.com/58702589/144607416-b78b67fb-4079-491e-8c47-66c75e6d1b80.png)

* ##### Список заявок **Пользователей** на возврат
![image](https://user-images.githubusercontent.com/58702589/144607618-0669c845-964b-4a0b-8668-d1363f4d5a4c.png)

* ##### Конкретный заказ (вид Администратора)
![image](https://user-images.githubusercontent.com/58702589/144609778-8caf0ff1-a852-4b62-a3dc-fbcaae562605.png)

* ##### Конкретная заявка на возврат (вид Администратора)
![image](https://user-images.githubusercontent.com/58702589/144609832-cd949038-c6d6-4ddf-9527-c4ec9de1f803.png)

* ##### Форма отказа администратором по возврату


### 3. Диаграмма пользовательских сценариев

*  Примечание : с ***любой*** страницы сайта можно вернуться на ***Главную***, достаточно кликнуть по иконке. На диаграмме не показано данного, чтобы не захламлять ее

* ##### Сценарий использования системы неавторизированным пользователем (**Гость**)
![Гость](https://user-images.githubusercontent.com/58702589/144587197-14b08c86-5da9-4a0c-a458-bfd0bba8ba23.png)

* ##### Сценарий использования системы авторизированным пользователем (**Пользователь**)
![Пользователь](https://user-images.githubusercontent.com/58702589/144651078-54664ad3-ec50-420d-bd70-375792bb2a7b.png)

* ##### Сценарий использования системы администратором (**Администратор**)
![Админ](https://user-images.githubusercontent.com/58702589/144603584-417954e2-82d6-47d5-ba7d-cdee00cbcd21.png)
