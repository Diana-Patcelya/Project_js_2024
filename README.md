# Project_js_2024
Проєкт містить три сторінки: `index.html`, `user-details.html` та `post-details.html`, які взаємодіють з API https://jsonplaceholder.typicode.com/ для отримання та відображення інформації про користувачів та їх пости.

## index.html
1. Отримує масив об'єктів з ендпоінта `https://jsonplaceholder.typicode.com/users`.
2. Виводить id та name всіх користувачів у окремих блоках.
3. Додає кнопку для переходу на сторінку `user-details.html` для детальної інформації про обраний користувач.

## user-details.html
4. Виводить всю інформацію про обраний користувач.
5. Додає кнопку "post of current user", при кліку на яку виводить title всіх постів поточного користувача.
6. Додає кнопку для переходу на сторінку `post-details.html` для детальної інформації про обраний пост.

## post-details.html
7. Виводить всю інформацію про обраний пост.
8. Нижче виводить коментарі до обраного поста.
