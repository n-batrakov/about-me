# Батраков Никита

.NET Core \ JavaScript разработчик

* [Опыт](#опыт)
* [О себе](#о-себе)
* [Проекты](#открытые-проекты)


## Опыт

Веб-приложения разного уровня сложности. От классических ASP.NET MVC приложений, до более интересных систем с несколькими сервисами, SPA-фронтендом и машинным обучением.

Последние два года активно разрабатывал на JavaScript.

Интересный опыт:

* Писал на .NET middle-tier системы с фронтендом на Angular и бэкендом на 1С. Налаживал коммуникации как между системами, так и между людьми.
* Писал фронтенд на React, компоненты на VueJS, расширения для браузеров, внутренних ботов для Slack.
* Проектировал и оценивал очень смелые и амбициозные идеи проектов. Учился трезво смотреть на вещи, задавать правильные вопросы, проявлять изобретательность.
* Много общался с менеджерами. Учился доносить свои мысли и понимать чужие.

Основные обязанности:

* Активное участие в проектировании архитектуры систем
* REST API (реализация, проектирование спецификаций в Swagger) на .NET Core и NodeJS
* CLI-утилиты на NodeJS
* аутентификация и авторизация
* Настройка билдов компонентов, CI \ CD, Docker, скрипты
* Нагрузочное тестирование
* Код-ревью и оценка технических заданий
* Написание документации

Технологический стэк:

* ОС: Linux, Windows
* Языки: C#, JavaScript (TypeScript), Python
* Хранение данных: MS SQL, PostgreSQL, Redis, MongoDb, InfluxDB, ElasticSearch
* Контейнеры: Docker
* Библиотеки и фреймворки: ASP.NET Core, React, Redux, RxJS, VueJS


## О себе

* Люблю проектирование, дизайн кода и систем. Не люблю преждевременную оптимизацию, микро-оптимизации и жертвоприношения производительности.
* Не боюсь новых технологий и языков. Всегда рад попробовать что-то новое. Но отношусь к этому практично, когда речь заходит о продуктовом коде.
* Хороший опыт в ООП благодаря .NET. Учил паттерны, SOLID, разбирался с UML.
* Нравится ФП, но за моноид в категории эндофункторов не поясню.
* Мне действительно интересно, что я делаю, и я хочу улучшаться и развиваться в этом.
* Готов давать фидбэк о рабочем процессе, предлагать улучшения, проявлять инициативу.
* Думаю о людях и пусть никто не уйдет обиженным. Делать жизнь людей проще - то, что мне нравится в работе, будь то мои коллеги или конечные пользователи.
* Свободно читаю и слушаю английский. Могу написать документацию на английском.
* Работаю удаленно больше года. Умею дисциплинировать себя, продуктивно работать и отдыхать, разделять работу и дом.


## Открытые проекты

### [node-bin-manager](https://github.com/olive-branch/node-bin-manager)

> TypeScript

Инструмент для NodeJS, аналогичный npm, но для произвольных бинарников.
Находит ссылки в `package.json`, скачивает, распаковывает, записывает на диск.


### [etlx](https://github.com/etlx/etlx)

> TypeScript, RxJS

Библиотека для написания скриптов ETL (Extract-Transform-Load),
т.е. набор функций для удобной работы с файловой и другими популярными системами.

Идея полностью аналогична [Apache Airflow](https://airflow.apache.org/).

Проект незакончен и медленно развивается.
Создавался ради доказательства возможности идеи (Proof of Concept).

Использовал подход монорепозитория с помощью Lerna.
Уделил много внимания подходу и дизайну библиотеки.


### [Text Better](https://github.com/n-batrakov/text-better)

> Gulp, Pug, SASS, Figma

Статический сайт с советами эффективной переписки.

Занимался всем - от написания текста и дизайна, до реализации.

Уделил внимание Доступности (a11y), SEO, размеру бандла.

Проект временно заморожен из-за недостатка свободного времени.


### [form-gather](https://github.com/n-batrakov/form-gather)

> TypeScript

Крошечная библиотека для сериализации HTML формы в объект. Аналогично классу `FormData`.

Уделил внимание тестированию, совместимости с браузерами, размеру библиотеки, дизайну.


### [Redmine Timey](https://github.com/n-batrakov/redmine-timey)

> TypeScript, React, Redux, WebPack

Приложение, интегрирующееся с таск-трекером [Redmine](https://www.redmine.org/),
предоставляющее альтернативный UI для работы со временем.

Занимался всем - дизайн, разработка сервера и клиента, деплой в виде Docker-контейнеров.

* Репозиторий содержит фронт на React и бэк на Fastify.
* Настроен свой билд с помощью Webpack.
* При разработке запуск сервера бэкенда и сервера статики производится одной командой.
  Билд происходит при изменении кода сервера или клиента.


### [OpenApiServer](https://github.com/n-batrakov/OpenApiServer)

> C#, ASP.NET Core, Swagger

Утилита для создания Mock-API на основе OpenAPI 3 (aka Swagger Spec).

Мотивация: при проектировании API с помощью Swagger-спецификаций, написанных вручную,
дать возможность фронтендерам быстро поднять тестовый API по этой спецификации.
А также проверить соответствие реального API созданной спецификации.

Итог: проект был доведен до первого рабочего прототипа, но невостребован из-за организационных причин.

* Уделил внимание дизайну и гибкости
* Покапался во "внутренностях" ASP.NET Core
* Задеплоил утилиту в виде NuGet Tool и npm бинаринков.


### [Secret Santa Bot](https://github.com/n-batrakov/secret-santa)

> TypeScript, Marble

Чат-бот для [Mattermost](https://mattermost.com/) для проведения тайного санты.

Серверный API написан на [Marble](https://github.com/marblejs/marble) - библиотека для создания REST API на RxJS.
