

Launch

uvicorn main:app --reload


http://127.0.0.1:8000 - тут будет приложение

http://127.0.0.1:8000/docs - тут будет дока swagger api


Инициализация миграций:

`alembic init migrations`


# main:app название файла: название переменной с экземпляром FastAPI
# --reload автоматически перезагружает если изменился код