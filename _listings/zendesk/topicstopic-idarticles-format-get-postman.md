{
  "info": {
    "name": "Sales Force Desk API Get Topic Articles",
    "_postman_id": "d3521a12-11bc-4383-8cb2-e006b48da822",
    "description": "Get topic articles.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Topics",
      "item": [
        {
          "id": "7074a38a-1ec3-42bc-98a1-065f4d1d30a0",
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
              "id": "f0246625-ea4f-475e-9350-8480d80a1a61"
            }
          ]
        },
        {
          "id": "dbbf7c86-7daa-433e-aafd-f48b7e102e2e",
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
              "id": "6922a7e6-c331-44cd-87b0-fd7e7d3d4b17"
            }
          ]
        },
        {
          "id": "a4a90459-f420-49ee-92a0-e8dc67f66636",
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
              "id": "158494aa-f441-459a-b525-12cdb9560124"
            }
          ]
        },
        {
          "id": "bbaf08e1-56fd-49e5-9cc5-0cde6b6acde7",
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
              "id": "d9eaf92e-44ce-49d5-8e53-9b4e1216d355"
            }
          ]
        },
        {
          "id": "9174835e-b22b-4725-ae85-bffef865f479",
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
              "id": "ef27a982-5d13-43ae-b665-f6f561cbdb86"
            }
          ]
        },
        {
          "id": "23144661-b355-4a75-b6dc-b4cec19d90fc",
          "name": "get-topic-articles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "topics/:topic_id/articles.json"
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
                  "id": "topic_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get topic articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ab8cdf9-ec7b-4bba-b7bd-0365eb335659"
            }
          ]
        }
      ]
    }
  ]
}