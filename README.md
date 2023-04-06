# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list https://monosnap.com/file/C6QuTbIaGAo2WcSeJvRRhHkac8E5X9

# Получаем контакт по id

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6 https://monosnap.com/file/WpORgeAKVM20DpXvJy0zEz7PSRBCyw

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22 https://monosnap.com/file/LLJfLsVhzk685N7WjkUzW3Usa0zmmy

# Удаляем контакт

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH https://monosnap.com/file/Vjq5ZJ5tc73UyoDS2Fi0FcAdvPsPkf
