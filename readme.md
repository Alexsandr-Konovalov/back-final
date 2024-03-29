# Бек-энд списка задач

Это часть финального проекта курса TryIT, отвечающая за хранение задач и работу с ними, припомощи REST API.

Описание функционала для приложения "To-Do List":

1. Создание и Управление Задачами:
      - Добавление задач с указанием заголовка, описания, срока выполнения и приоритета.
      - Управление списком задач, включая возможность добавления, редактирования, удаления и отметки о выполнении.

2. Организация Задач:
      - Группировка задач по категориям, меткам или проектам для удобства навигации и отслеживания.
      - Создание списков дел для различных областей жизни, работы или учебы.

3. Уведомления и Напоминания:
      - Настройка напоминаний о предстоящих задачах и событиях для своевременного выполнения задач.
      - Получение уведомлений по электронной почте, SMS или пуш-уведомлениям о важных сроках и задачах.

4. Поддержка Коллаборации:
      - Возможность совместного доступа к списку задач для работы в команде, семье или проектной группе.
      - Делегирование задач и задач с соответствующими участниками и установка сроков выполнения.

5. Персонализация и Настройка:
      - Настройка внешнего вида приложения, тем, цветовой схемы и макета для персонализации пользовательского опыта.
      - Установка предпочтений уведомлений, часового пояса и других параметров для удобства использования.

6. Аналитика и Отчетность:
      - Статистика выполненных задач, прогресса и эффективности по использованию To-Do List.
      - Генерация отчетов об активности, обзорах проектов и планах на будущее.

7. Интеграция с Календарем и Другими Приложениями:
      - Синхронизация To-Do List с календарем, электронной почтой, облачными сервисами и другими приложениями для удобства использования.

Приложение To-Do List предоставляет удобный и эффективный способ организовать свои задачи, управлять временными ресурсами и повысить продуктивность в повседневной деятельности.

## Системные требования

Для работы проекта необходимы:

- Node v16.20.0+
- npm v8.19.4+
- Docker Engine v20.10.16+
- docker-compose v2.6.0+

## Как запустить проект

Для запуска проекта, сначала необходимо установить зависимости, при помощи команды:

- npm install

И создать файл .env. В нем должны содержаться:

- PORT - число, номер порта, который будет слушать сервер.

После этого можно запустить проет или в обычном режиме:

- npm run build - Скомпилирует проект в файл index.js для запуска сервера в папку dist.

- npm run start - Запустит сервер.

Или в режиме разработчика:

- npm run dev - Скомпилирует проект, запустит его, будет обновлять и перезапускать при изменении кода.

Для запуска базы данных Redis, при помощи Docker, нужно в отдельном терминале запустить команду:

- docker-compose up
