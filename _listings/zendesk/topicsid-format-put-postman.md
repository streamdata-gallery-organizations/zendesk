{
  "info": {
    "name": "Sales Force Desk API Update Topic",
    "_postman_id": "79293fa6-b170-494e-83ce-834026cd34d0",
    "description": "Update topic.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Topics",
      "item": [
        {
          "id": "775cf51a-5087-4e7f-b717-655a1a2aa38e",
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
              "id": "cf56a582-66bd-4baa-86cf-1fe25679f11d"
            }
          ]
        },
        {
          "id": "107c676e-1f7b-4181-bfee-516f787660da",
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
              "id": "6862cc56-d286-4994-aaf9-7b59d9cad9ae"
            }
          ]
        },
        {
          "id": "48c89774-a885-4cc9-9c7b-ef533ef8c24d",
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
              "id": "f4e812e1-fe0b-4d76-bbbc-abd409945888"
            }
          ]
        },
        {
          "id": "4960e03e-8bfe-4dfc-b065-fb794015107f",
          "name": "update-topic",
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
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c2fea97-a1fa-4a44-aa21-390b5e0e216e"
            }
          ]
        },
        {
          "id": "d2ff2bd6-3f24-4a0f-bdeb-3d29c07a10a0",
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
              "id": "9759265e-7ee5-4ed5-9e32-29f97c58b1e8"
            }
          ]
        }
      ]
    }
  ]
}