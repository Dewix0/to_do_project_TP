# to_do_project_TP


__Запросы__


___Получение списка задач___ 


```
http://127.0.0.1:8000/api/tasks/ - GET

```

___Создвние задачи___


```

http://127.0.0.1:8000/api/tasks/ - POST

RAW JSON

{
  "title": "Проверка работы API",
  "description": "проверка сохраняется ли все в бд",
  "is_completed": false
}

```

___Редактирование___

```
http://127.0.0.1:8000/api/tasks/1/ - PUT

RAW JSON

{
  "title": "Проверка редактирования",
  "description": "проверка сохраняется ли все в бд",
  "is_completed": true
}

```

___Удаление___

```

RAW JSON

http://127.0.0.1:8000/api/tasks/3/ - DELETE

```