# mlflow-environment-docker-setup
MLFlow docker environment setup

## .env file exemple
    MYSQL_DATABASE=mlflow
    MYSQL_USER=mlflow
    MYSQL_PASSWORD=mlflow
    MYSQL_ROOT_PASSWORD=mlflow
    MLFLOW_PORT=7000
    MLFLOW_DIR_MODELS=/home/mlflow/mlruns
    
## Just run docker-compose to setup
    docker-compose up -d
