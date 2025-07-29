# BankJ - Банковская система на Java

![Java](https://img.shields.io/badge/Java-11%2B-blue)
![Swing](https://img.shields.io/badge/GUI-Swing%2FAWT-orange)
![SQLite](https://img.shields.io/badge/Database-SQLite-green)

Учебный проект банковской системы с графическим интерфейсом и базой данных.

## 📋 Описание
Клиентское приложение для имитации банковских операций:
- Открытие счета
- Внесение/снятие средств
- Просмотр баланса

## 🛠 Технологии
- **Язык:** Java 11+
- **Интерфейс:** Swing/AWT
- **База данных:** SQLite + JDBC

## 📂 Структура проекта
```
src/
│
├── GUI/ # Графический интерфейс
│ ├── LoginWindow.java # Окно авторизации
│ ├── MainMenu.java # Главное меню
│ ├── DepositWindow.java # Окно внесения средств
│ └── WithdrawWindow.java # Окно снятия средств
│
├── Model/ # Бизнес-логика
│ ├── Account.java # Модель банковского счета
│ ├── BankOperations.java # Операции с балансом
│ ├── Database/
│ │ ├── DatabaseConnector.java # Подключение к БД
│ │ └── SQLiteManager.java # Управление SQLite
│ └── Queries/
│ ├── UserQueries.java # Запросы пользователей
│ └── TransactionQueries.java # Запросы операций
│
├── Utils/ # Вспомогательные классы
│ ├── PasswordHasher.java # Хеширование паролей
│ └── InputValidator.java # Валидация ввода
│
└── Main.java # Точка входа в приложение
```

## 🚀 Запуск
1. Установите [Java JDK 11+](https://adoptium.net/)
2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш-логин/BankJ.git
