# Безпека програм та даних — навчальні виправлення

Базовий проєкт: [OWASP Juice Shop](https://github.com/juice-shop/juice-shop).
Базовий коміт: `717f5efa886b0417eeecb52378b03cf10567b7e2`.

Кожна гілка містить окреме виправлення відносно базового коміту; зміни не об'єднані між собою.

| Робота | Зміна | Гілка |
|---|---|---|
| ЛР4 | Перевірка належності кошика поточному користувачу | [fix/lab4-basket-idor](https://github.com/IvanMylenkyi/juice-shop-bpd-labs/tree/fix/lab4-basket-idor) |
| ЛР5 | Виведення пошукового запиту як тексту для усунення DOM XSS | [fix/lab5-xss](https://github.com/IvanMylenkyi/juice-shop-bpd-labs/tree/fix/lab5-xss) |
| ЛР6 | Параметризований запит моделі користувача під час входу | [fix/lab6-login-sqli](https://github.com/IvanMylenkyi/juice-shop-bpd-labs/tree/fix/lab6-login-sqli) |
| ІДЗ | Заміна слабкого початкового пароля адміністратора | [fix/idz-password-strength](https://github.com/IvanMylenkyi/juice-shop-bpd-labs/tree/fix/idz-password-strength) |
| ІДЗ | Визначення автора відгуку за поточною сесією | [fix/idz-forged-feedback](https://github.com/IvanMylenkyi/juice-shop-bpd-labs/tree/fix/idz-forged-feedback) |

Зміна Password Strength демонструє заміну пароля у навчальних початкових даних. Значення опубліковане у вихідному коді та не є секретом; цей підхід не забезпечує керування секретами для робочої системи.

Juice Shop — навмисно вразливий навчальний застосунок. Наведені зміни стосуються лише зазначених завдань і не усувають решту його вразливостей. Ліцензія та авторство вихідного проєкту збережені.
