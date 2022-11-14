# Общий репозиторий проекта

<hr>

## Краткое описание
 * Общедоступное **web**-приложение для выставление посещаемости студентов
 * Поддержка прав доступа на редактирование/просмотр информации
 * Адаптивность под любую образовательную организацию

<hr>

## Цели
 * Создать программную систему вида журнала учёта
 * Создать приложение с максимально удобным и практичным интерфейсом
 * Максимально обширные и информативные графики, статистика
 * Интеграции с **Telegram** и **VKontakte** для отвязки от веб версии
 * Обеспечить максимальную независимость от персональных данных пользователей

<hr>

## Компоненты программной системы
### Требования к компонентам
 * Все компоненты системы должны быть с минимальными зависимостями между собой
 * Все компоненты разрабатываются независимо друг от друга
 * Все компоненты обязаны осуществлять атоматизированное тестирование
 * Все компоненты обеспечены своей системой непрерывной интеграции и непрерывной доставкой (**CI/CD**)
 * Все компоненты расположены в собственных репозиториях VCS системы **GitHub**, имеют лицензию **MIT**
 * Все компоненты представляют из себя **Docker образы**, расположенные в реестре **ghcr.io**

### Список компонентов и их краткое описание
 * Frontend - Веб приложение.
<!-- > **timesheet-diplom-frontend.git** -->
 * Auth Backend - Серверное приложение, отвественное за авторизацию/аутентификацию пользователя.

 * API Backend - Серверное приложение, отвественное за управление табелем.
 
 * Telegram Backend - Бот для **Telegram**.

 * VK Backend - Бот для **VKontakte**.

<hr>

## Текущий репозиторий
> **Warning**
> Предназначен для серверной части, является связующим путиводителем для всех компонент