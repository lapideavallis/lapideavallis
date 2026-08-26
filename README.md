## <p align="center">Привет, меня зовут Сергей! 👋</p>


## <p align="center">[![image](https://github.com/user-attachments/assets/d3a64477-e064-4cf5-96a6-3c68bb4497c2)](https://t.me/GetITs)</p>



### 👨💻 Обо мне:

Занимаюсь разработкой и оптимизацией пайплайнов обработки данных. Строю надежные и масштабируемые ETL/ELT-процессы, обеспечивающие бизнес качественными данными для аналитики и машинного обучения. Ищу команду для профессионального роста.

### 🤘 Мои навыки:

- **Языки программирования:** Python (Pandas, PySpark), SQL (оконные функции, CTE, оптимизация запросов);
- **Инструменты оркестрации:** Apache Airflow (разработка DAG'ов, управление зависимостями, S3-хуки);
- **Хранилища и базы данных:** ClickHouse, PostgreSQL, Greenplum, опыт работы с партиционированием и шардированием;
- **Big Data экосистема:** Apache Spark (PySpark, Spark SQL), Kafka (основы потоковой обработки);
- **Инфраструктура и CI/CD:** Docker, Git, GitLab CI / GitHub Actions;
- **Облачные платформы:** Базовый опыт работы с Yandex Cloud / AWS (S3, EC2);
- **Методологии:** Понимание принципов Data Mesh, Data Vault, построения витрин данных для различных бизнес-задач;
- **Визуализация и отчеты:** Разрабатываю дашборды в Tableau и Redash для демонстрации результатов работы пайплайнов.

### 🛠️ Языки и инструменты :

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/-PySpark-E25A1C?style=flat&logo=apache-spark&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=flat&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat&logo=tableau&logoColor=white)

### 📖 Мои проекты:

| Название проекта | Описание проекта | Стек |
| :--- | :--- | :--- |
| **ETL для витрины мобильного приложения** | Разработал DAG в Airflow для ежедневной загрузки событий из Kafka в ClickHouse. Настроил агрегацию данных для витрины с ключевыми метриками (DAU, ARPU). Реализовал механизм обработки сбоев и повторных запусков. | `Python` `Airflow` `Kafka` `ClickHouse` |
| **Оптимизация хранилища в Greenplum** | Провел анализ и оптимизацию медленных запросов к витринам данных. Применил партиционирование таблиц по датам и переписал сложные CTE, сократив время выполнения отчетов с 15 до 2 минут. | `SQL` `Greenplum` |
| **Миграция данных с использованием PySpark** | Создал скрипт на PySpark для очистки и трансформации исторических данных (5+ лет) из сырых логов в S3. Обработал 500+ млн записей, применил оконные функции для дедупликации. | `PySpark` `S3` `Python` |
| **Система мониторинга пайплайнов** | Настроил отправку оповещений в Telegram о статусе выполнения DAG'ов в Airflow. Добавил логирование основных метрик (время выполнения, объем данных) для предотвращения простоя. | `Python` `Airflow` `API` |
| **Концепция Data Lakehouse** | В pet-проекте реализовал хранение данных в формате Parquet с использованием разделов по году/месяцу. Написал простые запросы с использованием Trino (Presto) для анализа. | `Docker` `Trino` `Parquet` |
