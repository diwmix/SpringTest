# Spring Boot Hello World Project

Цей проект демонструє базові можливості Spring Boot та включає три рівні складності:

## Рівень 3 (Базовий) - "Hello World" API

- REST-контролер, який повертає "Hello, World!" при зверненні до `/hello`
- Реалізовано в `HelloController.java`

## Рівень 4 (Середній) - "Динамічна веб-сторінка з Thymeleaf"

- Контролер для обробки запитів на `/greet`
- Thymeleaf шаблон для відображення привітання
- Реалізовано в `GreetingController.java` та `greeting.html`

## Рівень 5 (Просунутий) - "Сервісний рівень та управління користувачами"

- Модель користувача (`User.java`)
- Сервісний рівень для управління користувачами (`UserService.java`)
- Контролер для відображення списку користувачів (`UserController.java`)
- Thymeleaf шаблон для відображення списку користувачів (`users.html`)

## Вимоги

- Java 17 або вище
- Maven 3.6 або вище

## Запуск проекту

1. Клонуйте репозиторій
2. Перейдіть до директорії проекту
3. Виконайте команду:

```bash
mvn spring-boot:run
```

## Доступні ендпоінти

- `http://localhost:8080/hello` - базовий "Hello World" API
- `http://localhost:8080/greet` - сторінка привітання
- `http://localhost:8080/users` - список користувачів
