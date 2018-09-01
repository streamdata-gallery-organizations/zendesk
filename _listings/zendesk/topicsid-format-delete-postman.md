{
  "info": {
    "name": "Sales Force Desk API Delete Topic",
    "_postman_id": "0cd9c668-631b-4985-8f9b-0e1297b2c33a",
    "description": "Delete topic.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Topics",
      "item": [
        {
          "id": "9c386cfd-326b-45c1-a2c8-5beff6c0c2d1",
          "name": "get-topics",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/topics.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get topics."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48eefbc0-99de-4a30-b8be-6a6531a6902c"
            }
          ]
        },
        {
          "id": "372a0999-6b7c-4984-a8b4-ccd7eb1c45b6",
          "name": "create-topic",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/topics.json?format=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "730dc498-6743-4079-8c94-c3c2aff44850"
            }
          ]
        },
        {
          "id": "8b6eeb2c-18da-4c59-b96c-59e5eb37677a",
          "name": "delete-topic",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "topics/:id.json"
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
            "description": "Delete topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36c00b56-2625-4917-b2e9-d5bbdfae2cf2"
            }
          ]
        }
      ]
    }
  ]
}