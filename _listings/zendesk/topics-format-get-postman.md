{
  "info": {
    "name": "Sales Force Desk API Get Topics",
    "_postman_id": "5c2017ab-61fe-4769-9374-03e339fc2f5e",
    "description": "Get topics.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Topics",
      "item": [
        {
          "id": "06ad6d6f-6803-4027-9c08-dfa2eda44cf9",
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
              "id": "348ea1d0-65a9-4c58-a693-9ff161c13a05"
            }
          ]
        }
      ]
    }
  ]
}