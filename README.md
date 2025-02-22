## Завдання

Вам необхiдно клонувати `FastAPI`-застосунок, налаштувати його та запустити в `Docker`-контейнері. Після цього перевірите правильність роботи застосунку і переконатись в успішному підключенні до бази даних.

**Покрокова інструкція**

1. Використовуючи команду `git clone`, клонуйте репозиторій за [адресою](https://github.com/GoIT-Python-Web/Computer-Systems-hw02). Перейдіть у клонований каталог.
2. Створіть `Dockerfile` із вказівками для створення образу `Docker` застосунку.
3. Напишіть `docker-compose.yaml` з конфігурацією для застосунку та `PostgreSQL`.
4. Використайте `Docker Compose` для побудови середовища, команду `docker-compose up` для запуску середовища.

Коли ви використовуєте `Docker Compose`, кожен сервіс (контейнер) має власну мережу, і вони зазвичай не можуть звертатися один до одного за допомогою `localhost`. Замість цього, ви маєте використовувати назву сервісу в якості імені хоста.

5. Перевірте функціональність застосунку та доступність бази даних.
