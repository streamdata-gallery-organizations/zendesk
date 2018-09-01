{
  "info": {
    "name": "Sales Force Desk API Delete Article",
    "_postman_id": "7ef233a4-e31d-4659-81f6-b900e0fd0b21",
    "description": "Delete article.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Articles",
      "item": [
        {
          "id": "3e1b97f1-e11d-4c73-9d06-69898914435a",
          "name": "delete-article",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "articles/:id.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete article."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c1f1aa0-a1c4-47cc-9164-0633ea59555b"
            }
          ]
        }
      ]
    }
  ]
}