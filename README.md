1. consulting_API - серверное приложение API
- используемые библиотеки:
Microsoft.AspNetCore.Identity.EntityFrameworkCore (6.0.18) - работа с пользователями
Microsoft.EntityFrameworkCore.SqlServer (6.0.18) - работа с БД
- целевая платформа: .NET 6.0
- УЗ по умолчанию:
логин: admin
пароль: Aaaa11!!

- описание функций  API:
[Route("api/[controller]")]

[HttpGet("sitetext")]
https://localhost:44380/api/application/sitetext/ - получить все тексты сайта

[HttpPut("sitetext")]
https://localhost:44380/api/application/sitetext/ - изменение текстов главной страницы

[HttpGet("tagline")]
https://localhost:44380/api/application/tagline/ - получить все слоганы

[HttpGet("tagline/{id}")]
https://localhost:44380/api/application/tagline/{id} - получить слоган по Id

[HttpGet("randomtagline")]
https://localhost:44380/api/application/randomtagline - получить произвольный слоган по Id

[HttpGet("request")]
https://localhost:44380/api/application/request - получить все заявки

[HttpGet("request/{id}")]
https://localhost:44380/api/application/request/{id} - получить заявку по Id

[HttpPost("request")]
https://localhost:44380/api/application/request - добавить заявку

[HttpPut("request")]
https://localhost:44380/api/application/request - изменить статус заявки

[HttpGet("services")]
https://localhost:44380/api/application/services - получить все услуги

[HttpGet("services/{id}")]
https://localhost:44380/api/application/services/{id} - получить услугу по Id

[HttpPost("services")]
https://localhost:44380/api/application/services - добавить услугу

[HttpDelete("services/{id}")]
https://localhost:44380/api/application/services/{id} - удалить услугу

[HttpPut("services")]
https://localhost:44380/api/application/services - изменить услугу

[HttpGet("projects")]
https://localhost:44380/api/application/projects - получить все проекты

[HttpGet("projects/{id}")]
https://localhost:44380/api/application/projects/{id} - получить проект по Id

[HttpPost("projects")]
https://localhost:44380/api/application/projects - добавить проект

[HttpDelete("projects/{id}")]
https://localhost:44380/api/application/projects/{id} - удалить проект

[HttpPut("projects")]
https://localhost:44380/api/application/projects - редактировать проект с заменой картинки

[HttpPut("projectsnonepix")]
https://localhost:44380/api/application/projectsnonepix - редактировать проект без замены картинки

[HttpGet("blog")]
https://localhost:44380/api/application/blog - получить все блоги

[HttpGet("blog/{id}")]
https://localhost:44380/api/application/blog/{id} - получить блог по Id

[HttpPost("blog")]
https://localhost:44380/api/application/blog - добавить блог

[HttpDelete("blog/{id}")]
https://localhost:44380/api/application/blog/{id} - удалить блог

[HttpPut("blog")]
https://localhost:44380/api/application/blog - редактировать блог с заменой картинки

[HttpPut("blognonepix")]
https://localhost:44380/api/application/blognonepix - редактировать блог без замены картинки

[HttpGet("contacts")]
https://localhost:44380/api/application/contacts - получить все контакты

[HttpPost("contacts")]
https://localhost:44380/api/application/contacts - добавить контакт

[HttpDelete("contacts/{id}")]
https://localhost:44380/api/application/contacts/{id} - удалить контакт

[HttpPut("contactstexts")]
https://localhost:44380/api/application/contactstexts - изменение текстов страницы контактов

[HttpPut("contactnonepix")]
https://localhost:44380/api/application/contactnonepix - редактировать контакт без замены картинки

[HttpPut("contactwithpix")]
https://localhost:44380/api/application/contactwithpix - редактировать контакт с заменой картинки

[HttpGet("getpixbyname/{name}")]
https://localhost:44380/api/application/getpixbyname/{name} - получить картинку по имени файла

[HttpGet("getpix/{id}")]
https://localhost:44380/api/application/getpix/{id} - получить картинку по Id

[HttpGet("users")]
https://localhost:44380/api/application/users - получение всех пользователей

[HttpGet("users/{id}")]
https://localhost:44380/api/application/users/{id} - получение одного конкретного пользователя

[HttpPost("users")]
https://localhost:44380/api/application/users - добавление пользователя

[HttpDelete("users/{id}")]
https://localhost:44380/api/application/users/{id} - удаление пользователя

[HttpPut("users")]
https://localhost:44380/api/application/users - изменение пользователя

[HttpPost("login")]
https://localhost:44380/api/application/login - логин

[HttpPost("register")]
https://localhost:44380/api/application/register - регистрация

2. consulting_WEB - web-приложение
- используемые библиотеки:
Microsoft.AspNetCore.Identity.EntityFrameworkCore (6.0.18) - работа с пользователями
Microsoft.EntityFrameworkCore.SqlServer (6.0.18) - работа с БД
Newtonsoft.Json (13.0.3) - парсинг JSON
- целевая платформа: .NET 6.0
- УЗ по умолчанию:
логин: admin
пароль: Aaaa11!!

3. consulting_WPF - приложение для рабочего стола
- используемые библиотеки:
Microsoft.AspNetCore.Http (2.2.0) - работа с http запросами в API
Newtonsoft.Json (13.0.3) - парсинг JSON
- целевая платформа: .NET Framework 4.8
- УЗ по умолчанию:
логин: admin
пароль: Aaaa11!!

4. consulting_Bot - приложение для работы с Telegram ботом
- используемые библиотеки:
Microsoft.AspNetCore.Http (2.2.2) - работа с http запросами в API
Newtonsoft.Json (13.0.3) - парсинг JSON
Telegram.Bot (19.0.0) - управление телеграм-ботом
- целевая платформа: .NET 6.0
- УЗ по умолчанию:
логин: admin
пароль: Aaaa11!!
