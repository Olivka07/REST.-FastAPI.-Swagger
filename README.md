# REST. FastAPI. Swagger
# Выполнил: Пирюшов Александр

### Процесс развертывания

1. Клонируйте репозиторий
2. Установите зависимости
```
pip install -r requirements.txt
```
3. Запустите приложение
```
uvicorn app:app --reload
```

#### 2. Развертывание с docker

1. Клонируйте репозиторий

2. Соберите и запустите контейнер

```
docker-compose up --build
```