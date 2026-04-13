# Deskgram 2 для Telegram-автоматизации

![Deskgram 2 overview](assets/screenshots/hub__overview__ru.png)

Deskgram 2 — это платформа для автоматизации действий в Telegram: управления аккаунтами, массовых коммуникаций, AI-сценариев, парсинга аудитории, инвайта и инфраструктурной подготовки рабочих сеток аккаунтов. Этот репозиторий играет роль главного хаба и ведет в узкие гайды по конкретным модулям.

[Официальный сайт](https://deskgram2.com/) · [Telegram-бот](https://t.me/DG2welcomebot) · [Web preview](https://deskgram2.com/web-preview) · [Преимущества](https://deskgram2.com/advantages)

## Почему это удобно

| Что нужно руками | Что дает Deskgram 2 |
|---|---|
| Держать в голове десятки отдельных действий | Работать через единый интерфейс |
| Вести аккаунты, прокси и лимиты в разных местах | Управлять инфраструктурой централизованно |
| Разносить сценарии по разным софтам и таблицам | Запускать рассылки, парсинг, AI и инвайт в одной системе |
| Терять логи и статусы по задачам | Видеть статистику, терминал и историю выполнения |
| Сложно масштабировать потоки | Управлять многопоточностью и лимитами из интерфейса |

## Что можно автоматизировать

| Сценарий | Подходящие модули | Что получаете на выходе |
|---|---|---|
| AI-комментирование постов | Нейрокомментинг | Автоматические комментарии по новым публикациям |
| Массовая отправка сообщений в ЛС | Рассылка в ЛС | Поточные личные рассылки с лимитами и AI |
| Подготовка базы пользователей | Сбор аудитории | Парсинг и экспорт аудитории из чатов и групп |
| Рост чатов и каналов через приглашения | Инвайт | Инвайт по заранее собранной базе |
| Подготовка инфраструктуры под задачи | Панель аккаунтов, Прокси и Настройки | Рабочая база прокси, аккаунтов и системных параметров |

## Кому подойдет

- командам Telegram-маркетинга;
- владельцам каналов и сеток аккаунтов;
- специалистам по лидогенерации;
- операторам Telegram-автоматизации;
- тем, кто хочет соединить AI, рассылки и парсинг в одном рабочем контуре.

## Визуально внутри программы

![Accounts](assets/screenshots/accounts-list__main__ru.png)
![Tasks](assets/screenshots/tasks-list__main__ru.png)
![Proxy](assets/screenshots/proxy__table__ru.png)
![Settings](assets/screenshots/settings__main__ru.png)

## Ключевые гайды по сценариям

- [Нейрокомментинг](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram)
- [Рассылка в ЛС](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram)
- [Сбор аудитории](https://github.com/Deskgram-2/telegram-audience-parser-deskgram)
- [Массовые подписки](https://github.com/Deskgram-2/telegram-join-groups-deskgram)
- [Инвайт](https://github.com/Deskgram-2/telegram-invite-tool-deskgram)

## Инфраструктурные и системные гайды

- [Панель аккаунтов](https://github.com/Deskgram-2/telegram-account-manager-deskgram)
- [Диспетчер задач](https://github.com/Deskgram-2/telegram-task-manager-deskgram)
- [Управление прокси](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram)
- [Настройки автоматизации](https://github.com/Deskgram-2/telegram-automation-settings-deskgram)

## Готовые связки по шагам

- [Панель аккаунтов](https://github.com/Deskgram-2/telegram-account-manager-deskgram) -> [Прокси](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram) -> [Настройки](https://github.com/Deskgram-2/telegram-automation-settings-deskgram) -> [Сбор аудитории](https://github.com/Deskgram-2/telegram-audience-parser-deskgram) -> [Рассылка в ЛС](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram)
- [Панель аккаунтов](https://github.com/Deskgram-2/telegram-account-manager-deskgram) -> [Прокси](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram) -> [Массовые подписки](https://github.com/Deskgram-2/telegram-join-groups-deskgram) -> [Инвайт](https://github.com/Deskgram-2/telegram-invite-tool-deskgram)
- [Настройки автоматизации](https://github.com/Deskgram-2/telegram-automation-settings-deskgram) -> [Нейрокомментинг](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram) -> [Диспетчер задач](https://github.com/Deskgram-2/telegram-task-manager-deskgram)
- [Управление прокси](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram)

## Быстрый старт

1. Добавьте Telegram-аккаунты в систему.
2. При необходимости привяжите и проверьте прокси.
3. Настройте системные параметры и AI-провайдеров.
4. Выберите модуль под нужный сценарий.
5. Задайте лимиты, задержки, фильтры и запустите задачу.
6. Контролируйте логи, статистику и итоговый результат.

## Рекомендуемый путь по модулям

1. [Панель аккаунтов](https://github.com/Deskgram-2/telegram-account-manager-deskgram) — завести и проверить аккаунты.
2. [Прокси](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram) — подготовить рабочий пул.
3. [Настройки](https://github.com/Deskgram-2/telegram-automation-settings-deskgram) — подключить ключи и системные параметры.
4. [Сбор аудитории](https://github.com/Deskgram-2/telegram-audience-parser-deskgram) или [Массовые подписки](https://github.com/Deskgram-2/telegram-join-groups-deskgram) — подготовить базу и окружение.
5. [Рассылка в ЛС](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram) или [Инвайт](https://github.com/Deskgram-2/telegram-invite-tool-deskgram) — использовать базу в сценарии роста.
6. [Нейрокомментинг](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram) — подключить AI-активности для каналов.
7. [Диспетчер задач](https://github.com/Deskgram-2/telegram-task-manager-deskgram) — контролировать статусы и результаты.

## FAQ

### Это один модуль или целая система?

Это система из нескольких модулей. Главный репозиторий нужен как точка входа: он объясняет продукт и направляет в более узкие гайды.

### Какие разделы особенно важны на старте?

Обычно стартовый путь выглядит так: Панель аккаунтов -> Прокси -> Настройки -> нужный модуль -> Задачи.

### Есть ли AI-сценарии внутри Deskgram 2?

Да. В проекте уже есть AI-модули и связанные настройки для генерации комментариев, сообщений и ответов.

### Что есть в этом репозитории?

Это обзорная точка входа в Deskgram 2. Здесь собраны базовые сценарии использования, краткое описание платформы и ссылки на отдельные гайды по ключевым модулям.

## Полезные ссылки

- [Сайт Deskgram 2](https://deskgram2.com/)
- [Telegram-бот Deskgram 2](https://t.me/DG2welcomebot)
- [Web preview](https://deskgram2.com/web-preview)
- [Преимущества Deskgram 2](https://deskgram2.com/advantages)
