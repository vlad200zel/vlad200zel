<div align="center">

# Владислав Зеленков · vlad200zel

**Разработчик: веб-приложения, интеграции с нейросетями, ассистенты**

Пишу на C#, Java и Python. Собираю приложения целиком — от базы данных и API до интерфейса, — и подключаю к ним нейросети: текстовые и голосовые помощники, генерация, распознавание и синтез речи.

</div>

---

### Стек

**Языки**

![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)

**Веб-разработка**

![.NET](https://img.shields.io/badge/.NET%208-512BD4?logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?logo=aspnet&logoColor=white)
![Razor Pages](https://img.shields.io/badge/Razor%20Pages-512BD4)
![REST API](https://img.shields.io/badge/REST%20API-005571)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap%205-7952B3?logo=bootstrap&logoColor=white)

**Нейросети и голос**

![LLM API](https://img.shields.io/badge/LLM%20API-412991?logo=openai&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?logo=openai&logoColor=white)
![Speech-to-Text](https://img.shields.io/badge/Speech--to--Text-FF6F00)
![Text-to-Speech](https://img.shields.io/badge/Text--to--Speech-8E44AD)
![AI Assistants](https://img.shields.io/badge/AI%20Assistants-0A0A0A)

**Данные и инфраструктура**

![Databases](https://img.shields.io/badge/Базы%20данных-336791?logo=postgresql&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?logo=dotnet&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Hosting](https://img.shields.io/badge/Хостинг%20и%20деплой-2C3E50)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

---

### Что умею

| Направление | Что конкретно |
|---|---|
| **Нейросети в приложениях** | Подключаю LLM к продукту через API: диалоги, генерация текста, обработка запросов. Настраиваю промпты, контекст и обработку ответов модели |
| **Голосовые и текстовые ассистенты** | Собираю помощников полного цикла: распознавание речи → обработка запроса моделью → синтез ответа голосом. Текст и голос как два интерфейса к одной логике |
| **Интеграции и API** | Работаю с REST: разбор чужих API, авторизация, лимиты, обработка ошибок и таймаутов, кэширование ответов, fallback при недоступности сервиса |
| **Веб-приложения** | Делаю приложения на ASP.NET Core (Razor Pages) и Python: серверная логика, страницы, формы, валидация, интерактив на JavaScript без лишних фреймворков |
| **Базы данных** | Проектирую схему данных и пишу слой доступа за интерфейсом — так, чтобы хранилище можно было заменить (JSON → SQL → EF Core) без переписывания логики |
| **Хостинг и деплой** | Поднимаю приложение на сервере: окружение, порты, HTTPS, публикация и обновление версии, разбор логов при падении |
| **Алгоритмы** | Реализую поиск на графах (Дейкстра), перебор с оценкой по критерию, геометрию (хаверсин) — и умею честно оценить сложность своего решения |

---

### Проекты

| Проект | О чём | Стек |
|---|---|---|
| **[LogisticsWeb](https://github.com/vlad200zel/Logistic-web)** | Планирование доставки с оптимизацией маршрута **по прибыли**, а не по расстоянию: база клиентов, карта, расчёт доходов и расходов по каждому участку | .NET 8 · Razor Pages · Leaflet · OSRM |

**LogisticsWeb** — учебный проект, сделанный целиком: модель данных и JSON-хранилище, CRUD-интерфейс с автодополнением адресов, матрица дорожных расстояний из OSRM, поиск самой выгодной комбинации остановок (DFS + Дейкстра) и визуализация маршрута на карте. В README — описание, скриншоты, инструкция пользователя и разбор архитектуры.

---

### Как я работаю

- **Сначала модель данных, потом код.** Если хранилище спрятано за интерфейсом, его можно заменить, не ломая приложение.
- **Внешние сервисы отказывают.** Любой вызов API оборачиваю в обработку ошибок и держу запасной вариант.
- **Проект должен запускаться одной командой.** Иначе им никто не воспользуется — включая меня через месяц.

---

### Контакты

- GitHub: [@vlad200zel](https://github.com/vlad200zel)
- Проект: [Logistic-web](https://github.com/vlad200zel/Logistic-web)

<sub>Открыт к стажировкам и junior-позициям: backend, .NET / Python, интеграции с ИИ.</sub>
