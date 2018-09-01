{
  "info": {
    "name": "Sales Force Desk API Update Macro",
    "_postman_id": "a7bbf0ce-dc44-40a2-bb9f-e50738995639",
    "description": "Update macro.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Articles",
      "item": [
        {
          "id": "aaf8cba1-d2e9-4607-a25c-100edf01ecfe",
          "name": "get-article",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get article."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f820ce4-68c0-4efb-b76f-ffab356f64c3"
            }
          ]
        },
        {
          "id": "cfa35b54-e519-4835-bb89-5e997256c62e",
          "name": "update-article",
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
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update article."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6467817-207e-47ba-bca6-34298ebec4bf"
            }
          ]
        },
        {
          "id": "a60a06c2-173c-458f-b0f7-d4e9567ecdf3",
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
              "id": "fc1efa84-d6b4-43c6-9974-a4e504abb66d"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "4fad5ac9-fdaa-4229-8148-e6fcde13b521",
          "name": "get-cases",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/cases.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get cases."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f6cff9b-d788-43e7-ac77-2b9923c4af09"
            }
          ]
        },
        {
          "id": "6a7e4321-9c6a-4295-a318-6a9557044db2",
          "name": "get-case",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "cases/:id.json"
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
            "description": "Get case."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "404de74f-7eb8-4d14-9567-dab9ee2dee55"
            }
          ]
        },
        {
          "id": "e5d9ab62-1a83-453f-bba0-b042ee238c30",
          "name": "update-case",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "cases/:id.json"
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
            "description": "Update case."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba620e6f-5f9b-4596-b5bb-09b5a73d1fe8"
            }
          ]
        }
      ]
    },
    {
      "name": "Customers",
      "item": [
        {
          "id": "588ab498-44ab-4e46-9b19-7dd6e50042a1",
          "name": "get-customers",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/customers.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get customers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e06f353f-1aa7-49a1-b9ca-968c1cb46a05"
            }
          ]
        },
        {
          "id": "1464824b-e9ca-4574-884a-5e9c86de3a9f",
          "name": "create-customer",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/customers.json?format=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c41760de-41dd-4309-b790-3e5003303bf9"
            }
          ]
        },
        {
          "id": "a430ffa0-4f72-4b18-8fad-e7c72256beb2",
          "name": "create-customer-email",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/emails.json"
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
                  "id": "customer_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create customer email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cac85a50-bfd7-4e25-9c1f-2cccbbc067e2"
            }
          ]
        },
        {
          "id": "ec3edf55-22af-4c70-ad01-869fed6ab26f",
          "name": "update-customer-email",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/emails/:id.json"
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
                  "id": "customer_id",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Update customer email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af7ca689-3e96-46c6-8ecf-19b0cc1d87d7"
            }
          ]
        },
        {
          "id": "3629ec50-4687-401f-b0c0-af935d4a59e1",
          "name": "create-customer-phone",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/phones.json"
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
                  "id": "customer_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create customer phone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3761413-f8ba-4c00-98eb-30204bc06a18"
            }
          ]
        },
        {
          "id": "0efe98da-098a-40c5-aadf-d3a520720ebc",
          "name": "update-customer-phone",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/phones/:id.json"
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
                  "id": "customer_id",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Update customer phone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3636885d-b2bf-43b9-9220-0aa8dac68fc6"
            }
          ]
        },
        {
          "id": "edeecca4-f0eb-4d89-9b3f-e03a690953a0",
          "name": "get-customer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:id.json"
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
            "description": "Get customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1894282f-af11-43eb-91dc-40da4cbe8ca2"
            }
          ]
        },
        {
          "id": "2d2d4c4b-8ec4-4fd8-88f8-af4c17fb80f3",
          "name": "update-customer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:id.json"
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
            "description": "Update customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d504db43-51bf-414c-b232-9deda58d3332"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "7b2fdc7f-bc46-410c-b556-70430fa57101",
          "name": "get-groups",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/groups.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34379c9e-ba11-468f-88bb-fe39d22c7422"
            }
          ]
        },
        {
          "id": "58d03ffa-ec8c-461b-9fad-7f451f8757e5",
          "name": "get-group",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "groups/:id.json"
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
            "description": "Get group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5828484-91d7-48db-8207-a79bce4e0638"
            }
          ]
        }
      ]
    },
    {
      "name": "Interactions",
      "item": [
        {
          "id": "77bf1021-8a5d-4226-ac7e-e04d56f85910",
          "name": "get-interactions",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/interactions.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get interactions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "678b9d9a-f759-4fb3-886c-c41c7aedf9e6"
            }
          ]
        },
        {
          "id": "03694074-d106-45c0-b924-d7ac14e33b4e",
          "name": "create-interaction",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/interactions.json?format=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create interaction."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00c3448f-d5b0-40a3-a046-b6f8e20c17a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Macros",
      "item": [
        {
          "id": "39381d5e-6551-4d68-a0b4-eee28427f1e3",
          "name": "get-macros",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/macros.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get macros."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d54f60a4-bb55-4d86-95fa-deaa6b5b75c0"
            }
          ]
        },
        {
          "id": "5560641c-1c9e-4343-a216-dc4deee2a8dd",
          "name": "create-macro",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/macros.json?format=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create macro."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fe0fb8b-15cf-4f55-b581-5282b69f82cb"
            }
          ]
        },
        {
          "id": "73d2e29d-4128-443c-9205-adba30c3feca",
          "name": "get-macro",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "macros/:id.json"
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
            "description": "Get macro."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95a24178-f695-494a-a471-6775794aa5f1"
            }
          ]
        },
        {
          "id": "a280aa14-15c9-4092-be20-54cae913e702",
          "name": "update-macro",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "macros/:id.json"
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
            "description": "Update macro."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aabb63ff-98b7-4cc0-b056-d029e2df8d61"
            }
          ]
        },
        {
          "id": "404687da-14be-48df-8f16-5235a57631fc",
          "name": "delete-macro",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "macros/:id.json"
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
            "description": "Delete macro."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e08e5701-7e0f-41a8-ba2e-56e9e0ab278e"
            }
          ]
        }
      ]
    }
  ]
}