# bigdata-kafka-pipeline
 было сделанно недели две-три назад 
# Big Data: Kafka Pipeline

Пайплайн потоковой обработки данных через Apache Kafka.

## Задача
Построить систему: producer генерирует события → consumer обрабатывает → результат пишется в файл и БД.

## Стек
- Python 3
- kafka-python
- PostgreSQL
- Docker

## Задания
1. Поднять Kafka через docker-compose
2. Реализовать producer с генерацией событий
3. Реализовать consumer с фильтрацией
4. Записать обработанные данные в БД
5. Добавить логирование
