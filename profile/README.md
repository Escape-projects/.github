# Escape-projects

Backend-проекты на C# и .NET: от дипломного мессенджера на WCF до REST API с EF Core, Redis, тестами и Docker.

Организация — это портфолио: каждый репозиторий является самостоятельным проектом со своим README, архитектурой и инструкцией запуска.

---

## Проекты

| Проект                                                       | Что это                                                      | Стек                                                         | Год  |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :--- |
| [`LibraryAPI`](https://github.com/Escape-projects/LibraryAPI) | REST API для библиотеки: книги, авторы, аккаунты сотрудников, роли, JWT с refresh-токенами, кэш в Redis, 52 юнит-теста, запуск в Docker Compose | C#, .NET 10, ASP.NET Core, EF Core, SQL Server, Redis, xUnit, Docker | 2026 |
| [`GameChat`](https://github.com/Escape-projects/GameChat)    | Игровой мессенджер: личные сообщения, комнаты по играм, обмен сообщениями в реальном времени через callback-контракты WCF | C#, .NET Framework 4.8, WCF, TCP/IP, WinForms, SQL Server    | 2025 |
| [`ApexBliss`](https://github.com/Escape-projects/ApexBliss)  | Учёт компьютеров, клиентов и игровых сессий компьютерного клуба; первый учебный проект после перерыва | C#, .NET 10, Dapper, DI, Repository Pattern, SQL Server      | 2026 |

Самый показательный проект — **LibraryAPI**: он охватывает то, чем занимается backend-разработчик каждый день — контракты API, доступ к данным, аутентификацию и авторизацию, кэширование, обработку ошибок, тесты и контейнеризацию.

---

## Как проекты связаны

Три репозитория отражают один путь:

- **ApexBliss** — восстановление базы C# и первые архитектурные идеи (DI, Repository, Dapper, транзакции) на маленьком домене.
- **GameChat** — дипломный проект: клиент-серверная система с сетевым взаимодействием и push-уведомлениями, где основная сложность была в архитектуре, а не в UI.
- **LibraryAPI** — тот же стек, но с современными практиками: EF Core вместо ручного ADO.NET, JWT вместо паролей в открытом виде, параметризованные запросы, 52 теста, Docker, CI.

---

## Технологии в проектах

| Направление     | Что использовалось                                |
| :-------------- | :------------------------------------------------ |
| Язык            | C#, SQL, T-SQL                                    |
| Платформы       | .NET 10, .NET Framework 4.8, ASP.NET Core Web API |
| Доступ к данным | EF Core (Code First, миграции), Dapper, ADO.NET   |
| Базы данных     | SQL Server                                        |
| Кэш             | Redis, `StackExchange.Redis`                      |
| Аутентификация  | JWT (access + refresh с ротацией), BCrypt, роли   |
| Сеть            | WCF (`netTcpBinding`), callback-контракты, TCP/IP |
| UI              | WinForms, консольные клиенты                      |
| Тесты           | xUnit, Moq, EF Core InMemory                      |
| Инфраструктура  | Docker, Docker Compose, GitHub Actions, Git       |

---

## Контакты

- GitHub: [escape-re](https://github.com/escape-re)
- Telegram: [@escape_137](https://t.me/escape_137)
- Email: Denny2002@list.ru
