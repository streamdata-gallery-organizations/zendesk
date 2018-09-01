---
swagger: "2.0"
x-collection-name: Zendesk
x-complete: 0
info:
  title: Sales Force Desk API Update Customer Email
  description: Update customer email.
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