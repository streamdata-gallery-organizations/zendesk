{
  "info": {
    "name": "Sales Force Desk API Create Topic",
    "_postman_id": "43767ac4-affd-449b-8e4e-41eb62a2edad",
    "description": "Create topic.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Topics",
      "item": [
        {
          "id": "8d66e23e-9230-4fca-9909-70012fa974ee",
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
              "id": "a867c5ed-6f0a-478e-a082-7bbcafc931db"
            }
          ]
        },
        {
          "id": "d9abf332-c69e-437a-acf8-16f6f666dd92",
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
              "id": "32722fdc-fd4c-4df9-b3ea-d27bc63a3501"
            }
          ]
        }
      ]
    }
  ]
}