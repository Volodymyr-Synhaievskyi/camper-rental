Застосунок для оренди кампера, який складається з 3-х сторінок:

Домашня сторінка з загальним описом послуг, що надає компанія. Стилізація та оформлення на ваш розсуд. Сторінка, що містить каталог камперів різної комплектації, які користувач може фільтрувати за місцем знаходження, обладнанням та типом Сторінка з оголошеннями, які були додані користувачем в улюблені Зовнішній вигляд програми повинен складатися з навігації (оформлення на ваш розсуд) та області перегляду.

Технічне завдання

Відповідно до макету реалізувати картку оголошення про здачу кампера в оренду. На першій сторінці каталогу має рендеритися 4 оголошення, а їх решта - по кліку на кнопку Load more. У разі кліку по кнопці у вигляді серця на картці оголошення воно має додаватися до списку улюблених, а колір кнопки змінюватися. При оновленні сторінки має фіксуватись кінцевий результат дій користувача. Тобто, якщо додати оголошення в улюблені та оновити сторінку - то кнопка все одно залишається в стані улюбленого оголошення із відповідним кольором. У разі повторного кліку по кнопці у вигляді серця оголошення повинно бути видалене зі списку улюблених, а колір кнопки змінитись до початкового стану. У разі кліку по кнопці Show more має відкриватись модальне вікно з детальною інформацією про кампер. Модальне вікно повинно закриватись по кліку на кнопку у вигляді хрестика, по кліку на backdrop та натисканню на клавішу Esc. В модальному вікні міститься інформація щодо особливостей кампера і відгуків про нього. Відмалювання інформації має залежати від стану активної таби. В модальному вікні також міститься форма для оформлення бронювання камперу, що складається з полів name, email, booking date і comment. Поля name, email, booking date є обовʼязковими до заповнення і мають проходити перевірку на валідність введених значень.(У випадку невалідних даних форма не відправляється, у випадку валідної форми - сторінка оновлюється). Ціна оренди має бути прописана одним значенням (наприклад, 8000). В UI - виведено через кому (8000,00). Для роботи зі списком оголошень створiть свій персональний бекенд для розробки за допомогою UI-сервісу https://mockapi.io/. Створiть ресурс adverts. Використайте конструктор ресурсу та опишiть об'єкт оголошення згiдно опису нижче.

Критерії виконання

Верстка фіксована в рх, семантична та валідна Немає помилок в консолі браузера Обов’язкове використання Redux Для запитів використовується бібліотека Axios Робота виконана на нативному JS з використанням бандлеру (Vite, Parcel або ін.) або на React Інтерактивність працює відповідно до технічного завдання Код відформатований та без коментарів В репозиторії має бути описаний README.md Проєкт задеплоєний (наприкда, на github pages або netlify.com)
