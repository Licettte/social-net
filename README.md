## Social Net 

$\text{\ \color{lightblue}\   Использовано:\}$  

<details>
<summary>Spring Web MVC</summary>

Spring MVC — структура для создания слабо связанных веб-приложений, разделяющая основные аспекты их разработки: объекты, бизнес-логику и внешний вид программы.

</details>

<details>
<summary>Postgres</summary>
Postgres - это свободная объектно-реляционной СУБД. Наряду с MySQL
</details>

<details>
<summary>Liquibase</summary>
Для настройки миграций БД использовали Liquibase. Создали с помощью changeSet структуру базы данных. Накатили миграции.
</details>


<details>
<summary>Swagger</summary>
Swagger — это набор инструментов, который позволяет автоматически описывать API на основе его кода. API — интерфейс для связи между разными программными продуктами, и у каждого проекта он свой. Документация, автоматически созданная через Swagger, облегчает понимание API для компьютеров и людей.
Использовал как для чтения требуемых эндпоинтов, параметров запросов. Так и для автоматического создания документации по проекту.
</details>

<details>

<summary>Jooq</summary>
jOOQ — это DSL (предметно-ориентированный язык), который имитирует как стандартный, так и специфический для поставщика синтаксис SQL в Java API.
Использовали его для:
1. Создания сущностей из таблиц БД, которые накатили с помощью Liquibqse;
2. Для взаимодействия с БД.
</details>


<details>

<summary>Docker, Docker-compose</summary>
Использовал для deploy приложения на облачном сервере. Создал докер образы из сервисов, запушил из в dockerhub и развернул в одном контейнере docker compose. После развертывания БД, поднимал контейнер Liquibase и накатывал миграции для создания структуры БД.
</details>





