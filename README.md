## Привет! Меня зовут Александр👋
<p align="left">
  <strong>Python Developer • Django • Django REST Framework • PostgreSQL • Redis • Celery • Docker • CI/CD</strong>
</p>
<p align="left">
  📱 <strong>Telegram:</strong> <a href="https://t.me" target="_blank">@alexancore</a> 
  &nbsp;&nbsp;•&nbsp;&nbsp; 
  📧 <strong>Email:</strong> <a href="mailto:kokoralexander@yandex.ru">kokoralexander@yandex.ru</a>
</p>

## 🧑‍💻 **Обо мне**
Я инженер-разработчик на Python c 10+ лет бэкграундом в финансах и аудите (Deloitte, Ростех), и в разработке финансовых моделей. С 2023 года перешел на проектную деятельность. Специализируюсь на создании масштабируемых веб-приложений на Django, занимаюсь проектированием и разработкой производительной серверной логики, созданием масштабируемых REST API, автоматизацией процессов и настройкой инфраструктуры.

&nbsp;

* 📍 **Локация:** Москва
* 🎓 **Образование:** МГТУ им. Н.Э. Баумана

---

## 🛠️ Tech Stack

### Backend & API
![Static Badge](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=%23FFC61C)
![Static Badge](https://img.shields.io/badge/Django-%23092E20?style=for-the-badge&logo=django&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Django%20REST%20Framework%20(DRF)-%23A33035?style=for-the-badge)

### Asynchronous & Queues
![Static Badge](https://img.shields.io/badge/Celery-%2337814A?style=for-the-badge&logo=celery&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Celery%20Beat-%2300B67A?style=for-the-badge&logo=celery-beat&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Redis-%23FF4438?style=for-the-badge&logo=redis&logoColor=%23FFFFFF)

### Databases & Tools
![Static Badge](https://img.shields.io/badge/PostgreSQL-%234169E1?style=for-the-badge&logo=PostgreSQL&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Pandas-%23150458?style=for-the-badge&logo=Pandas&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/JWT%20(JSON%20Web%20Tokens)-%23000000?style=for-the-badge&logo=JWT%20(JSON%20Web%20Tokens)&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Swagger%20%2F%20ReDoc%20(OpenAPI)-%2385EA2D?style=for-the-badge&logo=Swagger&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/psycopg3-%236644F8?style=for-the-badge&logo=psycopg3&logoColor=%23FFFFFF)

### DevOps, Frontend & Testing
![Static Badge](https://img.shields.io/badge/Docker-%232496ED?style=for-the-badge&logo=docker&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Nginx-%23009639?style=for-the-badge&logo=nginx&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/GitHub%20Actions-%232088FF?style=for-the-badge&logo=GitHub%20Actions&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/React-%2361DAFB?style=for-the-badge&logo=react&logoColor=%23000000)
![Static Badge](https://img.shields.io/badge/Pytest-%230A9EDC?style=for-the-badge&logo=Pytest&logoColor=%23FCFBFA)
![Static Badge](https://img.shields.io/badge/Yandex%20Cloud-%235282FF?style=for-the-badge&logo=yandexcloud&logoColor=%23FCFBFA)

---

## 🚀 Портфолио проектов

### 🚚 [LogiTrack SPA Service](https://github.com/AlexanderKokorinV/LogiTrack_SPA_Service)
**Современная высоконагруженная веб-платформа (SPA) для автоматизации диспетчеризации, мониторинга и аналитики транспортных рейсов логистической компании.**

* **Стек технологий:** Python, Django, DRF, PostgreSQL, React, Nginx, Docker, GitHub Actions, Coverage.
* **Что сделано:** Разработал клиент-серверную архитектуру на связке *React* и *DRF* с откликом интерфейса в *150–300 мс*. Внедрил Server-side Pagination в *PostgreSQL*, снизив сетевой трафик на 99%. Настроил *Nginx* в качестве reverse-proxy, контейнеризировал проект через *Docker Compose* и развернул автоматический CI/CD в *Yandex Cloud*.

### ✉️ [Mailing Manager Project](https://github.com)
**Автоматизированный веб-сервис для создания, администрирования и аналитики маркетинговых рассылок с многоуровневым кэшированием данных.**

* **Стек технологий:** Python, Django, PostgreSQL, Redis, Celery, Celery Beat, Pytest, Bootstrap 5.
* **Что сделано:** Настроил планирование рассылок через *Celery + Celery Beat*. Разработал пакетную (*Batch*) оптимизацию записи логов в *PostgreSQL*, снизив дисковую нагрузку. Внедрил защиту от спам-петель на уровне воркеров. Развернул двухуровневое кэширование данных (*Redis* + HTTP-заголовки `Cache-Control`) и спроектировал трехуровневую ролевую модель доступа (RBAC).

### 🗓️ [Habits Tracker Project](https://github.com)
**Отказоустойчивая бэкенд-часть (Web API) для SPA-приложения по трекингу полезных привычек с автоматической системой асинхронных напоминаний в Telegram.**

* **Стек технологий:** Python, Django REST Framework (DRF), PostgreSQL, Redis, Celery, Celery Beat, JWT, Swagger, Pytest/Coverage, Docker, Docker Compose, CI/CD.
* **Что сделано:** Реализовал RESTful API с кастомными валидаторами на уровне *Django Serializers* для контроля сложной бизнес-логики. Настроил безопасную аутентификацию по *JWT*. Интегрировал связку *Celery + Redis* для асинхронной отправки уведомлений в Telegram API по расписанию *Celery Beat*. Подключил *Swagger (drf-yasg)* и покрыл код тестами на 87%.

### 📊 [Vacancies Tracker (ETL)](https://github.com)
**Автоматизированный инструмент для мониторинга рынка труда и анализа вакансий крупнейших работодателей в реальном времени.**

* **Стек технологий:** Python, PostgreSQL, hh.ru API, `psycopg2`.
* **Что сделано:** Разработал ETL-пайплайн для сбора данных через официальное API hh.ru. Спроектировал реляционную схему данных (*One-to-Many*) в *PostgreSQL*. Написал класс `DBManager` со сложными аналитическими SQL-запросами (расчет средних зарплат, фильтрация по навыкам). Архитектура построена строго по принципам *SOLID (SRP, OCP)*.

### 🏦 [Bank Accounts Analyzer](https://github.com)
**Инструмент для автоматического анализа банковских выписок, расчета финансовой аналитики и мониторинга рыночных данных.**

* **Стек технологий:** Python, Pandas, APILayer (REST API), Pytest, `unittest.mock`.
* **Что сделано:** Реализовал парсинг, очистку и обработку транзакционных данных из Excel-файлов с помощью библиотеки *Pandas*. Настроил интеграцию с внешними REST API для получения актуальных курсов валют и котировок индекса S&P500. Написал алгоритмы расчета финансовых метрик и обеспечил 100% покрытие бизнес-логики тестами с использованием *Mock* и *Patch*.

---

## 📬 Контакты для связи

Открыт к интересным предложениям и готов выполнить тестовое задание!

* 📱 **Telegram:** [@alexancore](https://t.me)
* 📧 **Email:** [kokoralexander@yandex.ru](mailto:kokoralexander@yandex.ru)
* 🌐 **Сайт-визитка:** [alexander-python-backend-fastapi.ru](https://alexander-python-backend-fastapi.ru)
