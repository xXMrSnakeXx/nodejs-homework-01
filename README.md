# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://monosnap.com/file/bbYzSAeRECtcEiDThoPrFczJfJJCBf

# Получаем контакт по id

node index.js --action get --id 5
https://monosnap.com/file/aK93hVPE5mlC14qpKP61qfBpdQWnK8

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/yrzPQUqQ7ip28qTDVwy4tALd7BpwjC

# Удаляем контакт

node index.js --action remove --id=3
https://monosnap.com/file/T2lFaeyRrWhTfBOWSO2i6W1LIKfcKC
