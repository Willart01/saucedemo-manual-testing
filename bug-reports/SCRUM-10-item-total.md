**Сумма товаров Item Total отображается с лишними знаками после запятой на странице Checkout: Overview**



**Приоритет:** Low


**Шаги воспроизведения:**



1. [Зайти на страницу авторизации](https://www.saucedemo.com/) 
2. Войти в аккаунт (login:standard\_user, password:secret\_sauce)
3. Добавить в корзину товары: Sauce Labs Backpack, Sauce Labs Bike Light, Sauce Labs Bolt T-Shirt, Sauce Labs Fleece Jacket
4. Перейти в корзину с помощью иконки корзины в правом верхнем углу
5. &#x20;Нажать кнопку Checkout
6. Ввести информацию о покупателе (First name: Test, Last Name: Price, Zip/index code: 1234)
7. Нажать на кнопку Continue



**Ожидаемый результат:** В поле Item Total указана сумма всех товаров в заказе с двумя знаками после запятой: $105.96



**Фактический результат:** В поле Item total указана сумма $105.96000000000001



**Окружение:**

* ОС и версия: Windows 11 25H2
* Браузер и версия: Yandex Browser 26.8.0.0
* Тестовая среда: [Swag Labs](https://www.saucedemo.com/)


**Скриншот баг-репорта в Jira**
![Скриншот баг-репорта в Jira](attachments/SCRUM-11-jira.png)







