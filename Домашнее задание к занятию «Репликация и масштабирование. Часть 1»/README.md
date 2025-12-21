# Домашнее задание к занятию "`Репликация и масштабирование. Часть 1`" - `Бурыкин Кирилл`

### Задание 1

Master-Slave:

· Master - он только пишет данные 

· Slave - только читает эти данные 

· Данные идут в одну сторону: Master>Slave

· Если Master упал то запись невозможна

· Простая настройка

Master-Master:

· Оба сервера равны - оба могут и писать, и читать

· Данные синхронизируются в обе стороны

· Если один упал - второй работает

· Возможны конфликты при одновременной записи

· Сложная настройка

### Задание 2

<img width="678" height="122" alt="image" src="https://github.com/user-attachments/assets/6cd5639b-e833-4188-8060-ddbc65891b64" />

<img width="517" height="354" alt="image" src="https://github.com/user-attachments/assets/e5378aec-8c3f-49db-9931-04620955ab0d" />

<img width="1481" height="280" alt="image" src="https://github.com/user-attachments/assets/cf3796d3-18ef-4793-ab51-dd1b33c04945" />
