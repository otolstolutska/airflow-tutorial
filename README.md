# Airflow hello world project
Project for studing airflow

# Initial setup

Make expected directories and set an expected environment variable
```
mkdir -p ./dags ./logs ./plugins
echo -e "AIRFLOW_UID=$(id -u)" > .env
```

Initialize the database
```
docker-compose up airflow-init
```

Start up all services
```
docker-compose up
```
# Acceder à l'interface 

http://localhost:8080/

# Visualisation 

![image](https://user-images.githubusercontent.com/4661178/170865307-7f3ff654-0517-4ada-b04b-08d0217e8368.png)
