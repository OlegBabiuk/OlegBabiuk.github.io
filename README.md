 ## Виконане тестове завдання відповідно до технічного завдання.
 #### Технічне завдання:
1. __Створити веб-сторінку, на якій буде форма з кнопкою Submit__.
2. __На сторінці повинні бути наступні поля для вводу__:
      + First name* (text) 
      + Last name* (text) 
      + Birthday* (date + datepicker) 
      + Gender* (radio button) 
      + Country* (select) 
      + Email* (email) 
      + Password* (password) 
      + Address* (text) 
      + Notes (textarea) 
3. __На сторінці повинні бути виконані наступні вимоги__:

| №        | Умови           | Виконання  |
| ------------- |:-------------:| -----:|
| 1.     | При натисканні submit повинна відбуватись валідація даних, введених користувачем. |![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 2.     | Елементи з не валідними даними підсвічуються червоним кольором. Повідомлення з деталями помилки показуються під полем.      |  ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 3. | Валідація повинна відбуватись за допомогою дата атрибутів, наприклад, якщо в елемента є data-validation=”email”, то валідними даними в цьому полі будуть тільки e-mail (використай регулярні вирази для email валідації)      |    ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 4. |   * означає що поле обов’язкове для вводу.    |    ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 5. |   Текстові поля (text) дозволяють всі символи окрім ' та ".   |    ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 6. |  При натисканні на поле birthday повинен відкриватись datepicker.     |    ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 7. |  На кожен тип помилки повинно бути окреме повідомлення. Наприклад: якщо email поле пусте - “This field is required”. Якщо ж введено не валідний імейл - “Email address is not valid.”     |    ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 8. |  Для виконання завдання можна використовувати jQuery UI.     |    ![mark](https://OlegBabiuk.github.io/icon/cross.ico) |
| 9. |  Не використовуй плагіни для валідації даних.     |    ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
| 10. |   При проходженні валідації покажи alert(‘Validation passed.’).    |    ![mark](https://OlegBabiuk.github.io/icon/mark.ico) |
