---
swagger: "2.0"
x-collection-name: Zendesk
x-complete: 0
info:
  title: Sales Force Desk API Get Macro
  description: Get macro.
  version: v2
host: yoursite.desk.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /articles/{id}.{format}:
    delete:
      summary: Delete Article
      description: Delete article.
      operationId: delete-article
      x-api-path-slug: articlesid-format-delete
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Articles
      - Format
    get:
      summary: Get Article
      description: Get article.
      operationId: get-article
      x-api-path-slug: articlesid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Articles
      - Format
    put:
      summary: Update Article
      description: Update article.
      operationId: update-article
      x-api-path-slug: articlesid-format-put
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Articles
      - Format
  /cases.{format}:
    get:
      summary: Get Cases
      description: Get cases.
      operationId: get-cases
      x-api-path-slug: cases-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Format
  /cases/{id}.{format}:
    get:
      summary: Get Case
      description: Get case.
      operationId: get-case
      x-api-path-slug: casesid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Format
    put:
      summary: Update Case
      description: Update case.
      operationId: update-case
      x-api-path-slug: casesid-format-put
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Format
  /customers.{format}:
    get:
      summary: Get Customers
      description: Get customers.
      operationId: get-customers
      x-api-path-slug: customers-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
    post:
      summary: Create Customer
      description: Create customer.
      operationId: create-customer
      x-api-path-slug: customers-format-post
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
  /customers/{customer_id}/emails.{format}:
    post:
      summary: Create Customer Email
      description: Create customer email.
      operationId: create-customer-email
      x-api-path-slug: customerscustomer-idemails-format-post
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Emails
      - Format
  /customers/{customer_id}/emails/{id}.{format}:
    put:
      summary: Update Customer Email
      description: Update customer email.
      operationId: update-customer-email
      x-api-path-slug: customerscustomer-idemailsid-format-put
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Emails
      - Format
  /customers/{customer_id}/phones.{format}:
    post:
      summary: Create Customer Phone
      description: Create customer phone.
      operationId: create-customer-phone
      x-api-path-slug: customerscustomer-idphones-format-post
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Phones
      - Format
  /customers/{customer_id}/phones/{id}.{format}:
    put:
      summary: Update Customer Phone
      description: Update customer phone.
      operationId: update-customer-phone
      x-api-path-slug: customerscustomer-idphonesid-format-put
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Phones
      - Format
  /customers/{id}.{format}:
    get:
      summary: Get Customer
      description: Get customer.
      operationId: get-customer
      x-api-path-slug: customersid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
    put:
      summary: Update Customer
      description: Update customer.
      operationId: update-customer
      x-api-path-slug: customersid-format-put
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
  /groups.{format}:
    get:
      summary: Get Groups
      description: Get groups.
      operationId: get-groups
      x-api-path-slug: groups-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Format
  /groups/{id}.{format}:
    get:
      summary: Get Group
      description: Get group.
      operationId: get-group
      x-api-path-slug: groupsid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Format
  /interactions.{format}:
    get:
      summary: Get Interactions
      description: Get interactions.
      operationId: get-interactions
      x-api-path-slug: interactions-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Interactions
      - Format
    post:
      summary: Create Interaction
      description: Create interaction.
      operationId: create-interaction
      x-api-path-slug: interactions-format-post
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Interactions
      - Format
  /macros.{format}:
    get:
      summary: Get Macros
      description: Get macros.
      operationId: get-macros
      x-api-path-slug: macros-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Macros
      - Format
    post:
      summary: Create Macro
      description: Create macro.
      operationId: create-macro
      x-api-path-slug: macros-format-post
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Macros
      - Format
  /macros/{id}.{format}:
    delete:
      summary: Delete Macro
      description: Delete macro.
      operationId: delete-macro
      x-api-path-slug: macrosid-format-delete
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Macros
      - Format
    get:
      summary: Get Macro
      description: Get macro.
      operationId: get-macro
      x-api-path-slug: macrosid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Macros
      - Format
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---