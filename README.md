# devops-school-docker

## 1
   Написать Dockerfile для frontend располагается в директории /frontend, собрать и запустить

### 2
   Написать Dockerfile для backend который располагается в директории /lib_catalog(для сборки контейнера необходимо использовать файл /lib_catalog/requirements.txt), для работы backend необходим postgresql, т.е. необходимо собрать 2 контейнера:
   
   * backend
   * postgresql
   
   Осуществить сетевые настройки, для работы связки backend и postgresql

### 3
   Написать docker-compose.yaml, для всего проекта, собрать и запустить

### Критерий оценки финального задания
   Dockerfile должны быть написаны согласно пройденным best practices
   
   Для docker-compose необходимо использовать локальное image registry
   
   В docker-compose необходимо сетевые настройки 2 разных интерфейса(bridge), 1 - для фронта, 2 - для бека с postgresql

### 4.* 
   Осуществить сборку проекта самим docker-compose команда docker-compose build(при использовании этого подхода необходимо исключить 2 пункт из критерии оценки)

