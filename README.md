# Практика 7. REST. FastAPI. Swagger
# Выполнил: Бабаев Шохрухбек

### Процесс развертывания

1. Клонируйте репозиторий

2. Установите зависимости
```bash
pip install -r requirements.txt
```
3. Запустите приложение
```bash
uvicorn app:app --reload
```

#### 2. Развертывание с docker

1. Клонируйте репозиторий

2. Соберите и запустите контейнер

```bash
docker-compose up --build
```