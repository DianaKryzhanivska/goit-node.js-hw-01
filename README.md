Cкріншоти виконання команд:

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
https://monosnap.com/file/LzxuS9gJBrsgohSGv1eKOG8glvF4WR

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/VZRmfpLFK14d83li2QM3C0ArJGvjM1

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/AHBYpw5xWI8YmNzRg5PjZuVUJ5Afys

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/iB35hc56uEdRbFrhnBFe5JJZgmWIor
