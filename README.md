# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list

# Получаем контакт по id

node index.js --action get --id 5

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

# Удаляем контакт

node index.js --action remove --id=3

// invokeAction({ action: 'list' }); // invokeAction({ action: 'get', id }); // invokeAction({
action: 'add', ...newContact }); // invokeAction({ action: 'remove', id: idTest });