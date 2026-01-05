# Практичне заняття «Робота з Dockerfile та Docker Compose»

### Результат:<br>
1. Створено усі необхідні файли: <br>
- app.py — Flask-застосунок, який обробляє HTTP-запит і збільшує лічильник переглядів у Redis.
- requirements.txt — список Python-залежностей, необхідних для роботи застосунку.
- Dockerfile — опис інструкцій для збірки Docker-образу з Flask-застосунком.
- docker-compose.yml — конфігурація для запуску та зв’язку контейнерів Flask і Redis.
2. docker compose up --build корректно відрацював<br><br>
<img width="1028" height="420" alt="image" src="https://github.com/user-attachments/assets/dd2d47f0-4aea-4031-b926-765717e40c6c" /><br><br>

3. Лічильник на сайті працює корректно<br>
<img width="429" height="175" alt="image" src="https://github.com/user-attachments/assets/b7df809d-6764-4e03-b48b-493ef37d7cfb" />

### Висновок
Під час виконання практичної роботи було створено Dockerfile та конфігурацію Docker Compose. Запущено багатосервісний застосунок Flask з використанням Redis у контейнерах. Отримано практичні навички збірки образів, запуску сервісів та керування контейнерами за допомогою Docker Compose.
