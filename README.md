# MIN SIK KIM
<img src="./images/profile.jpg" width="150">

## Introduction
Hello there, I'm `MIN SIK KIM`.</br>
I am a programmer that interested about `Big-data`, `AI` and `Web`.

## Contacts
- **Email**: minsigi8911@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/mskim89
- **Blog**: https://mingsigi.tistory.com/

## Tech Stacks
- Languages
    - `Python`
        - Libraries
            1. `Elasticsearch`
            2. `Pandas`
            3. `MongoClient`
            4. `Pillow`
            5. `asyncio`
            6. `Minio`
            7. `Numpy`
            8. `Matplotlib`
            9. `tensorflow`
            10. `Keras`
            11. `scikit-learn`
    - `Node.js`
        - Frameworks
            1. `Koa`
            2. `AdminJS`
    - `Data Query Language`
        1. `SQL` (`MySQL`, `MariaDB`)
        2. `NoSQL`(`MongoDB`)
        3. `Elasticsearch Query DSL`
        4. `graphQL`
- Tools
    - Headless Content Management System
        - [Strapi](https://strapi.io/)
    - Search Engine
        - [Elastic Stack](https://www.elastic.co/guide/index.html)
    - Docker & Docker Compose
        - [Docker](https://docs.docker.com/)
        - [Docker Compose](https://docs.docker.com/compose/)
    - Object Storage Server
        - [MinIO](https://min.io/)
    - Secure
        - Key Management System
            - [Valut](https://www.vaultproject.io/)
        - Key Encryption System
            - [MINIO-kes](https://github.com/minio/kes)
    - Database
        1. SQL
            - `Database`
                - [Mysql](https://www.mysql.com/)
                - [MariaDB](https://mariadb.org/)
                - [Postgresql](https://www.postgresql.org/)
            - `DB Manager`
                - [DBeaver](https://dbeaver.io/)
            - `ORM`
                - [Sequlize](https://sequelize.org/)
        2. NoSQL
            - `Database`
                - [MongoDB](https://www.mongodb.com/)
            - `DB Manager`
                - [Robo 3T](https://robomongo.org/)
            - `ORM`
                - [MongoClient](https://mongodb.github.io/node-mongodb-native/)

## Career
### *DDH Inc.*
- **Period**: `09/01/2021` - `05/31/2023`
- **Position**: `BackEnd Engineer`
- **Description**: `Build Backend environment` (`angular` &rarr; `node.js`)
- **Tech Stack**: 
    - *Program Language*
        > `Node.js`
        - Develop BackEnd Server

        > `Python`
        - Data handling (`Analysis`, `CRUD`, `Generate graphQL schema file`)
    - *Frameworks*
        > `Koa`
        - Used this for build API server instead `expressJS`
    - *Containers*
        > `Docker`
        - The API server was containerized with Docker

        > `Docker Compose`
        - Various services were configured as Docker containers and conveniently operated through Docker Compose.
    - *CI/CD*
        > `GitLab`
        - Deployment automation was configured through GitLab CI/CD pipeline.
    - *Database*
        > `MySQL`
        - Solution(`DDHAIM`) base DB
        > `Mongo`
        - Solution(`Labeling Tool`) base DB
    - *Web Security*
        > `Nginx`
        - SSL/TLS certification (`Let's Encrpyt`)
    - *API Security*
        > `Redis`
        - JWT token managing
    - *File Managing*
        > `MinIO`
        - File server (original, thumbnail files saved buckets in here)
        > `Vault (HashiCorp)`
        - KMS (Key Management system). MinIO's file encryption key management.
        > `MinIO-KES`
        - Key Encryption System between MinIO and Vault.
    - *Cloud Infrastructure*
        > `AWS`
        - External URL routing and hosting
    - *Backend Framework*
        > `Strapi` & `graphQL`
        - Control RDBMS with Strapi and graphQL handle data through query

### *Ezfarm Inc.*
- **Period**: `04/01/2020` - `08/13/2021`
- **Position**: `BigData Engineer`
- **Description**: `Build BigData Infrastructure` (based from `Elasticsearch`)
- **Tech Stack**: 
    - *Program Language*
        > `Python`
        - Data ETL between raw data and elasticsearch
    - *Search Engine*
        > `Elasticsearch`
        - Data search with query DSL
            - Query optimization (Korean search, aggregation search and .etc)
        > `Logstash`
        - Data Load
            1. Database data (via `jdbc` plugin)
            2. Log data (via `filebeat`)
            3. JSON data (Logstash `Input`, `Output` plugins)
            4. CSV data (via `file` plugin)
        > `Kibana`
        - Data visualization
            - Visualize data loaded into Elasticsearch with graphs.
### *Wayties Inc.*
- **Period**: `03/02/2018` - `02/28/2019`
- **Position**: `Assistant Research Engineer`
- **Description**: `V2X data analysis` & `Development analysis tool`
- **Tech Stack**: 
    - *Program Language*
        > `HTML`
        - Develop WebPage

        > `Javascript`
        - Develop basic Frontend

        > `Node.js`
        - Develop BackEnd Server
    - *Frameworks*
        > `expressJS`
        - Used this for build API server
    - *Database*
        > `Mongo`
        - V2X(`Vehicle-to-Everything`) data save here
    - *Search Engine*
        > `Elasticsearch`
        - Data search with query DSL
            - Query optimization (Korean search, aggregation search and .etc)
        > `Logstash`
        - Data Load
            1. Database data (via `jdbc` plugin)
            2. Log data (via `filebeat`)
            3. JSON data (Logstash `Input`, `Output` plugins)
            4. CSV data (via `file` plugin)
        > `Kibana`
        - Data visualization
            - Visualize data loaded into Elasticsearch with graphs.

## Projects Experience
### *Data analysis in `Labeling Tool` solution*
- **Period**: `03/01/2023` - `05/01/2023`
- **Description**: `Labeled data analysis`
- **Role**: `Lost data was recovered, abnormal data was removed during the restoration process, and misaligned image data locations were normalized.`
- **기술 스택**:
    - *Program Language*
        > `Python`
        - The tasks specified in the role have been automated.
    - *Database*
        > `Mongo`
        - Solution(`Labeling Tool`) base DB

### *DDHAIM*
- **Period**: `09/01/2021` - `05/31/2023`
- **Description**: `Solution of the teeth correction`
- **Role**: `Rebuild Backend Environment` (`Angular` &rarr; `Node.js`)
- **Tech Stacks**: 
    - *Program Language*
        > `Node.js`
        - Develop BackEnd Server

        > `Python`
        - Generate graphQL schema
            - Deprecated after using `Strapi`
    - *Frameworks*
        > `Koa`
        - Used this for build API server instead `expressJS`
    - *Containers*
        > `Docker`
        - The API server was containerized with Docker

        > `Docker Compose`
        - Various services were configured as Docker containers and conveniently operated through Docker Compose.
    - *CI/CD*
        > `GitLab`
        - Deployment automation was configured through GitLab CI/CD pipeline.
    - *Database*
        > `MySQL`
        - Solution(`DDHAIM`) base DB
    - *Web Security*
        > `Nginx`
        - SSL/TLS certification (`Let's Encrpyt`)
    - *API Security*
        > `Redis`
        - JWT token managing
    - *File Managing*
        > `MinIO`
        - File server (original, thumbnail files saved buckets in here)
        > `Vault (HashiCorp)`
        - KMS (Key Management system). MinIO's file encryption key management.
        > `MinIO-KES`
        - Key Encryption System between MinIO and Vault.
    - *Cloud Infrastructure*
        > `AWS`
        - External URL routing and hosting
    - *Backend Framework*
        > `Strapi` & `graphQL`
        - Control RDBMS with Strapi and graphQL handle data through query

### 라벨링 툴 백엔드 개발
- **기간**: [시작일 - 종료일]
- **설명**: [프로젝트 간략 설명]
- **역할**: [본인이 수행한 역할 상세 기술]
- **기술 스택**: [사용한 기술들]

### 3D 라벨링 툴 백엔드 개발
- **기간**: [시작일 - 종료일]
- **설명**: [프로젝트 간략 설명]
- **역할**: [본인이 수행한 역할 상세 기술]
- **기술 스택**: [사용한 기술들]

### 대구 TP 치과솔루션 백엔드 개발
- **기간**: [시작일 - 종료일]
- **설명**: [프로젝트 간략 설명]
- **역할**: [본인이 수행한 역할 상세 기술]
- **기술 스택**: [사용한 기술들]

## Education
- **학위:** [학위 종류] in [전공] - [학교명], [취득 연도]
- **학위:** [학위 종류] in [전공] - [학교명], [취득 연도]

## Skills
- [국비 지원 등에서 배운 기술교육내용을 쓰면 되겠네]

## 추가 정보
[여기에는 취미, 관심사, 기타 자기소개 등을 추가]

---

저의 이력서를 간략히 소개드렸습니다. 더 많은 정보와 프로젝트 세부 내용은 제 GitHub 블로그([블로그 링크])에서 확인하실 수 있습니다. 혹시 궁금한 점이나 협업 제안이 있으시면 언제든지 연락 부탁드립니다!


