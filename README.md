# go-api
Exemple of dockerizing Go / Go Fiber REST API with Postgres, air

```sh
    $ docker-compose up -d --build
```

Them go to http://127.0.0.1:3000/

you can POST question/answer in http://127.0.0.1:3000/fact

```json
    {
        "question":"quelle est la couleur du cheval noir?",
        "answer": "noir"
    }
```

Get all questions/answers http://127.0.0.1:3000