# OTUS. Репозиторий домашних заданий по курсу MLOps

**Репозиторий домашних заданий**  
**Курс MLOps**  
**Образовательная платформа «Otus»**

## О курсе

Данный репозиторий содержит описание домашних заданий по курсу **MLOps (Machine Learning Operations)** - практическому курсу по внедрению систем машинного обучения в промышленную эксплуатацию.

## Структура проекта

Проект представляет собой сквозную разработку системы обнаружения мошеннических финансовых операций с использованием современного стека MLOps инструментов.

### Сквозной кейс: Antifraud-система

> **Бизнес-задача**: Создание системы машинного обучения для выявления мошеннических финансовых транзакций в реальном времени с возможностью автоматического обновления модели и масштабирования под нагрузку.

### Домашние задания

| № | Тема | Технологии | Описание |
|---|------|------------|----------|
| [**hw_01**](./hw_01/) | Анализ задачи | Business Analysis, MISSION Canvas | Формализация бизнес-требований и проектирование системы |
| [**hw_02**](./hw_02/) | Облачная инфраструктура | Yandex Cloud, Terraform, Spark | Настройка облачной инфраструктуры и хранилища данных |
| [**hw_03**](./hw_03/) | Очистка данных | Apache Spark, PySpark, Data Quality | Анализ качества данных и создание пайплайна очистки |
| [**hw_04**](./hw_04/) | Feature Store | Feast | Создание системы управления признаками |
| [**hw_05**](./hw_05/) | Оркестрация | Apache Airflow, DAGs | Автоматизация процессов с помощью Airflow |
| [**hw_06**](./hw_06/) | ML Pipeline | MLflow, Model Training | Переобучение модели и трекинг экспериментов |
| [**hw_07**](./hw_07/) | Валидация модели | A/B Testing, Model Validation | Статистическая валидация и A/B тестирование |
| [**hw_08**](./hw_08/) | Потоковая обработка | Apache Kafka, Streaming | Инференс на потоке данных |
| [**hw_09**](./hw_09/) | Контейнеризация | Docker, Kubernetes, CI/CD | API модели и контейнеризация |
| [**hw_10**](./hw_10/) | Production | K8s, Prometheus, Grafana | Продакшн развертывание и мониторинг |

## Технологический стек

### Облачная платформа
- **Yandex Cloud** - облачный провайдер
- **Terraform** - Infrastructure as Code

### Обработка данных
- **Apache Spark** - распределенная обработка больших данных
- **PySpark** - Python API для Spark
- **Apache Kafka** - потоковая обработка данных

### Machine Learning
- **MLflow** - управление экспериментами и моделями
- **Feast** - Feature Store для управления признаками
- **Scikit-learn / PySpark ML** - библиотеки машинного обучения

### Оркестрация и автоматизация
- **Apache Airflow** - оркестрация ML пайплайнов
- **GitHub Actions** - CI/CD пайплайны

### Контейнеризация и развертывание
- **Docker** - контейнеризация приложений
- **Kubernetes** - оркестрация контейнеров
- **Helm** - пакетный менеджер для Kubernetes

### Мониторинг
- **Prometheus** - сбор метрик
- **Grafana** - визуализация метрик
- **Alertmanager** - система уведомлений

## Результаты обучения

После прохождения курса и выполнения всех домашних заданий вы получите:

### Практические навыки
- ✅ Проектирование архитектуры ML-систем
- ✅ Работа с облачными платформами (Yandex Cloud)
- ✅ Настройка инфраструктуры через код (Terraform)
- ✅ Создание пайплайнов обработки данных (Apache Spark)
- ✅ Управление признаками (Feast Feature Store)
- ✅ Оркестрация ML-процессов (Apache Airflow)
- ✅ Трекинг экспериментов (MLflow)
- ✅ Валидация и A/B тестирование моделей
- ✅ Потоковая обработка данных (Apache Kafka)
- ✅ Контейнеризация и CI/CD (Docker, Kubernetes)
- ✅ Мониторинг и алертинг (Prometheus, Grafana)

### Готовое портфолио
- 🎯 **End-to-end MLOps проект** с полным циклом разработки
- 🏗️ **Инфраструктурный код** для быстрого развертывания
- 🔄 **CI/CD пайплайны** для автоматизации процессов
- 📊 **Система мониторинга** для продакшн среды
- 📚 **Документация** и лучшие практики

## Требования

### Технические требования
- **Python 3.8+**
- **Docker & Docker Compose**
- **Terraform**
- **kubectl**
- **Аккаунт в Yandex Cloud**

### Предварительные знания
- Основы Python и SQL
- Базовые знания машинного обучения
- Понимание принципов работы с командной строкой Linux
- Опыт работы с Git и GitHub

## Структура репозитория

```
MLOps/
├── hw_01/          # Анализ задачи и планирование
├── hw_02/          # Облачная инфраструктура (Yandex Cloud, Terraform)
├── hw_03/          # Обработка и очистка данных (PySpark)
├── hw_04/          # Feature Store (Feast)
├── hw_05/          # Оркестрация (Airflow)
├── hw_06/          # ML Pipeline (MLflow)
├── hw_07/          # Валидация модели (A/B Testing)
├── hw_08/          # Потоковая обработка (Kafka)
├── hw_09/          # Контейнеризация (Docker, Kubernetes)
├── hw_10/          # Production развертывание (K8s, Prometheus, Grafana)
└── README.md       # Описание репозитория
```

## Полезные ссылки

### Документация
- [Yandex Cloud Documentation](https://cloud.yandex.ru/docs)

### Инструменты
- [Terraform Yandex Provider](https://registry.terraform.io/providers/yandex-cloud/yandex/latest/docs)
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)
- [Feast Documentation](https://docs.feast.dev/)
- [Airflow Documentation](https://airflow.apache.org/docs/)
- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [Kafka Documentation](https://kafka.apache.org/documentation/)
- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)
- [Helm Documentation](https://helm.sh/docs/)
- [Prometheus Documentation](https://prometheus.io/docs/)
- [Grafana Documentation](https://grafana.com/docs/)

---

**Образовательная платформа «Otus»**  
**Курс MLOps - Machine Learning Operations**
