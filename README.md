
# Solva Tech DevOps 

## 1. Основы Linux
- Создание директории devops_test в домашнем каталоге.

` mkdir devops_test `
- Создание пустого файла readme.txt в созданной директории.

` touch readme.txt `
- Показать текущий путь в терминале.

` pwd ` 
![image](https://github.com/user-attachments/assets/60ee9887-ed2b-44eb-b825-f13f95b49915)


## 2. Основы Git
Задание: Выполните следующие действия с использованием Git:
- Создайте новый локальный репозиторий.
` cd devops_test `

` git init`
- Создайте файл test.txt, добавьте в него текст “Hello DevOps”.
` touch test.txt `

` nano test.txt `

` Hello DevOps `

` control+O -> control+X`

- Закоммитьте изменения с сообщением “Initial commit”.
` git add test.txt `

` git commit -m "Initial commit" `

- Покажите историю коммитов.
` git log `

![image](https://github.com/user-attachments/assets/99cfe2ec-cbb7-4125-8a57-658fb38d9983)


## 3. Основы сетевых технологий
- Что такое IP-адрес и для чего он используется?
IP-адрес - это уникальный идентификатор устройства в сети, благодаря которому его возможно находить и передавать данные. 

- Назовите основные отличия между протоколами TCP и UDP.
TCP - медленнее, но безопаснее, чем UDP. Это происходит из-за того, что в TCP все данные передаются по определенному порядку, с полной проверкой данных и для этого требуется выполнение соединения, тогда как в UDP соединение не требуется, оно может быть открытым и он не гарантирует полную доставку всех данных в отправленном порядке. 

## 4. Программирование (Bash или Python)
- Напишите скрипт на Bash или Python, который выводит числа от 1 до 10.
`for i in range(10):`

`print(i + 1)` 

## 5. Логическое мышление
- В одном здании находится три лампочки, управляемые тремя выключателями в другой комнате. Как определить, какой выключатель к какой лампочке относится, если вы можете зайти в комнату с лампочками только один раз?

- Ответ: в комнате с выключателями включу рандомные 2, выключу первую, вторую оставлю гореть. после пойду в комнату с лампочками. Та лампочка, что горит, первый выключатель, та что теплая, второй выключатель, третья соответственно третья.

