# test_json
Тестовое задание в Mindbox по проверке вызова сервиса для получение информации о пользователе (Postman/REST API/JSON).

***

Задание: У разработчиков клиента не получается вызвать сервис получения информации о пользователе. Посмотрите присланный клиентом запрос, вызовите веб-сервис самостоятельно и пришлите ответ.

Запрос:
POST https://api.mindbox.ru/v3/operations/sync?endpointId=hiring.Website&operation=get.user
- Content-Type: application/json; charset=utf-8
- Accept: application/json
- Authorization: Mindbox secretKey="QQ5oyl5DLBhKeLrQO1A2"
- Body: {"customer": {"email": "demo@mindbox.cloud"}}

Исходная операция возвращала Success согласно спецификации.
Добавил операцию и настроил поля: https://hiring.mindbox.ru/campaigns/operations/295/help . Итоговый ответ в файле 

# Решение в файле ResultMindbox.json

***
