# Курс "Технологии хранения больших данных"
            
## Описание курса
Курс для магистерской программы Университета ИТМО ([Проектирование и разработка систем искусственного интеллекта](https://abit.itmo.ru/program/master/ai_systems)).
Обзорный курс содержит 8 лекций и 8 практических занятий.      


### Регламент занятий
Занятие идёт с одним перерывом.    
  
|||
|---|---|
|**18:40**|**начало 1 пары**|      
|19:25|перерыв 5 минут| 
|**19:30**|**начало второй части 1 пары**|      
|20:15|перерыв 10 минут|       
|**20:25**|**начало 2 пары**|       
|21:10|перерыв 5 минут|       
|**21:15**|**начало второй части 2 пары**|     
|21:50|конец 2 пары|   
           

### Обзор курса


**1. Введение**      
Определение больших данных.     
Основные характеристики: объем, скорость, разнообразие, достоверность, ценность.     
Архитектура хранилищ больших данных.      
Основные источники больших данных (социальные сети, сенсоры, транзакции и т.д.).    
Краткий обзор технологий хранения и обработки больших данных.    
Примеры применения больших данных в различных отраслях.    

**2. Популярные NoSQL хранилища и СУБД: Scylla/Cassandra, HDFS, HBase, Redis, Memcached, ElasticSearch/Solr, MongoDB, ClickHouse**     
Scylla/Cassandra: Колонко-ориентированные базы данных.    
HDFS: Распределенная файловая система для хранения больших данных.    
HBase: Колонко-ориентированная база данных поверх HDFS.     
Redis и Memcached: Базы данных типа ключ-значение для кэширования.     
ElasticSearch и Solr: Поисковые системы для полнотекстового поиска.     
MongoDB: Документо-ориентированная база данных.     
ClickHouse: Колонко-ориентированная СУБД для аналитики.  
       
**3. Модели хранения данных – строковая модель, колоночная, графовая, документная**     
Строковая модель: Принципы реляционных баз данных (RDBMS), таблицы, строки, столбцы.    
Колоночная модель: Принципы колоночных баз данных, отличие от строковых, примеры (Cassandra, HBase).    
Графовая модель: Принципы графовых баз данных, узлы и ребра, примеры (Neo4j).    
Документная модель: Принципы документно-ориентированных баз данных, JSON и BSON форматы, примеры (MongoDB).     

**4. Поисковые индексы и эффективное хранение и применение индексов на диске – хэш-таблицы, деревья поиска, пространственные индексы, полнтоекстовый поиск**             
Хэш-таблицы: Принципы работы, преимущества и недостатки.    
Деревья поиска (B-деревья, R-деревья): Принципы работы, примеры.    
Пространственные индексы: Принципы работы и применение.    
Полнотекстовый поиск: Принципы и примеры использования (ElasticSearch, Solr). 

**5. Языки запросов к различным моделям хранения – SQL, Cypher**      
SQL: Основы языка запросов для реляционных баз данных.    
Cypher: Язык запросов для графовых баз данных.    
CQL (Cassandra Query Language): Язык запросов для Cassandra.    
MongoDB Query Language (MQL): Язык запросов для MongoDB.       

**6. OLTP vs. OLAP, аналитические базы данных и эффективное представление данных для выполнения аналитических задач**    
OLTP (Online Transaction Processing): Принципы и применение.    
OLAP (Online Analytical Processing): Принципы и применение.    
Аналитические базы данных: Примеры (Redshift, BigQuery, ClickHouse).    
Эффективное представление данных: Методы и инструменты визуализации данных (Tableau, Power BI).             

**7. Форматы хранения данных – таблицы, protobuf, avro**     
Таблицы: Формат данных в реляционных базах.    
Protocol Buffers (Protobuf): Формат данных, разработанный Google.    
Avro: Формат данных для Hadoop и экосистемы больших данных.    

**8. Озера данных, витрины данных**           
Озера данных (Data Lakes): Принципы, архитектура, примеры использования.    
Витрины данных (Data Marts): Принципы, архитектура, примеры использования.    
Интеграция озер данных и витрин данных: Примеры и подходы.            

### Опросы    
Предопрос: https://forms.gle/JBoJHaRE7SBffjWm6     

### Журнал занятий      
Основная информация о занятиях (включая отметку о зачёте): 
https://docs.google.com/spreadsheets/d/1a0PCWAtHOpnlTHo4IEXa-qLP7OpGkFsQaN0T6QlsZF4/edit?gid=0#gid=0     

### Телеграм-канал курса
[https://t.me/BigDataCourse2024](https://t.me/BigDataCourse2024) 

### Список литературы:     
[Список рекомендованной литературы](https://github.com/iradche/Big-data-2024-course/blob/main/literature.md)

### Оценка за курс   
Для получения зачёта по курсу необходимо выполнить следующие задания:     
1. Выступить с докладом на тему технологий хранения больших данных (тему доклада необходимо [выбрать из списка тем](https://docs.google.com/spreadsheets/d/e/2PACX-1vRaPxQWPS8hGtKUTEAruRp-uI-7QA4DmGy8TIIijuVRvQNRcVajz9Kvw2Y1K2tO91do1S8UM15qbbqc/pubhtml?gid=1698065974&single=true) заранее и согласовать с преподавателем).    
2. Спроектировать информационную систему на основе больших данных (тематику ИС необходимо [выбрать из списка](https://docs.google.com/spreadsheets/d/e/2PACX-1vRaPxQWPS8hGtKUTEAruRp-uI-7QA4DmGy8TIIijuVRvQNRcVajz9Kvw2Y1K2tO91do1S8UM15qbbqc/pubhtml?gid=427201977&single=true) заранее и согласовать с преподавателем).   
3. Выполнить задания курса по SQL.     
4. Участвовать в семинарах, проводимых в течение всего курса.    



