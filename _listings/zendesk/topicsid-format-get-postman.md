{
  "info": {
    "name": "Sales Force Desk API Get Topic",
    "_postman_id": "49d2bfc1-5411-47ec-a04b-6f8cce4b447c",
    "description": "Get topic.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Topics",
      "item": [
        {
          "id": "67345d02-a0ea-48d7-9b28-84ce0cec633a",
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
              "id": "be45e1e4-933e-4864-a458-ded10be6aac9"
            }
          ]
        },
        {
          "id": "cfd6610e-51f5-4edc-a5e3-18060f3b077b",
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
              "id": "7f63c57f-b59e-4a4a-82c1-52b4d2dc97b7"
            }
          ]
        },
        {
          "id": "d0a4d55a-62d3-4adf-af48-77c7f1dbf050",
          "name": "get-topic",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5127f37-edff-46ff-9904-e8dc966def1c"
            }
          ]
        },
        {
          "id": "e22faa96-30a8-4884-9675-e387b7644fc4",
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
              "id": "3c35082c-aeb1-463e-9554-e714d1b9ba9c"
            }
          ]
        }
      ]
    }
  ]
}