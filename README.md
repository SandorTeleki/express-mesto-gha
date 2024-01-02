(English version below)

# Проект Mesto фронтенд + бэкенд


### Настройка бейджей статуса тестов
Перед началом работы над проектом рекомендуется исправить бейджи, отражающие статус прохождения тестов.
Для этого замените разметку бейджей на следующий фрагмент, подставив вместо `${имя_пользователя}` и `${имя_репозитория}` соответствующие значения.

```
[![Tests for sprint 13](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-13-sprint.yml/badge.svg)](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-13-sprint.yml) 

[![Tests for sprint 14](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-14-sprint.yml/badge.svg)](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-14-sprint.yml)
```
Тесты сломались во время спринта.

### Директории

`/routes` — папка с файлами роутера  
`/controllers` — папка с файлами контроллеров пользователя и карточки   
`/models` — папка с файлами описания схем пользователя и карточки  
  
Остальные директории вспомогательные, создаются при необходимости разработчиком

### Запуск проекта

1. Клонировать репозиторий:  
`git clone https://github.com/SandorTeleki/express-mesto-gha.git`
2. Установить зависимости:  
`npm i`
3. Запускает сервер    
`npm run start`
4.  Запускает сервер с hot-reload  
`npm run dev`

&copy; 2022 Шандор Телеки

---

# Mesto project frontend + backend

### Customizing test status badges
Before starting work on the project, it is recommended to fix the badges reflecting the status of passing tests.
To do this, replace the markup of the badges with the following snippet, substituting `${user_name}` and `${repository_name}` with the appropriate values instead of `${user_name}`.

```
[![Tests for sprint 13](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-13-sprint.yml/badge.svg)](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-13-sprint.yml) 

[![Tests for sprint 14](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-14-sprint.yml/badge.svg)](https://github.com/${имя_пользователя}/${имя репозитория}/actions/workflows/tests-14-sprint.yml)
```
The tests broke during the sprint and were subsequently not used.

### Directories

`/routes` - folder with router files  
`/controllers` - folder with user and card controller files   
`/models` - folder with files of user and card schemes description.  
  
Other directories are auxiliary, created when needed.


### Project Startup

1. Clone the repository:  
`git clone https://github.com/SandorTeleki/express-mesto-gha.git`.
2. Install dependencies:  
`npm i`.
3. Starts the server    
`npm run start`.
4.  Starts the server with hot-reload  
`npm run dev`

&copy; 2022 Sandor Teleki

