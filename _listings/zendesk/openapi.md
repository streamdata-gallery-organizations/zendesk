---
swagger: "2.0"
x-collection-name: Zendesk
x-complete: 1
info:
  title: Sales Force Desk API
  description: build-deep-integrations-expose-your-service-to-influential-smb-customers-or-just-make-desk-com-work-the-way-you-want-
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
    put:
      summary: Update Macro
      description: Update macro.
      operationId: update-macro
      x-api-path-slug: macrosid-format-put
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
  /macros/{macro_id}/actions.{format}:
    get:
      summary: Get Macro Actions
      description: Get macro actions.
      operationId: get-macro-actions
      x-api-path-slug: macrosmacro-idactions-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: macro_id
      responses:
        200:
          description: OK
      tags:
      - Macros
      - Macro
      - Actions
      - Format
  /macros/{macro_id}/actions/{type}.{format}:
    get:
      summary: Get Macro Action
      description: Get macro action.
      operationId: get-macro-action
      x-api-path-slug: macrosmacro-idactionstype-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: macro_id
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Macros
      - Macro
      - Actions
      - Type
      - Format
    put:
      summary: Update Macro Action
      description: Update macro action.
      operationId: update-macro-action
      x-api-path-slug: macrosmacro-idactionstype-format-put
      parameters:
      - in: path
        name: format
      - in: path
        name: macro_id
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Macros
      - Macro
      - Actions
      - Type
      - Format
  /topics.{format}:
    get:
      summary: Get Topics
      description: Get topics.
      operationId: get-topics
      x-api-path-slug: topics-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Topics
      - Format
    post:
      summary: Create Topic
      description: Create topic.
      operationId: create-topic
      x-api-path-slug: topics-format-post
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Topics
      - Format
  /topics/{id}.{format}:
    delete:
      summary: Delete Topic
      description: Delete topic.
      operationId: delete-topic
      x-api-path-slug: topicsid-format-delete
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Topics
      - Format
    get:
      summary: Get Topic
      description: Get topic.
      operationId: get-topic
      x-api-path-slug: topicsid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Topics
      - Format
    put:
      summary: Update Topic
      description: Update topic.
      operationId: update-topic
      x-api-path-slug: topicsid-format-put
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Topics
      - Format
  /topics/{topic_id}/articles.{format}:
    get:
      summary: Get Topic Articles
      description: Get topic articles.
      operationId: get-topic-articles
      x-api-path-slug: topicstopic-idarticles-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: topic_id
      responses:
        200:
          description: OK
      tags:
      - Topics
      - Topic
      - Articles
      - Format
    post:
      summary: Create Topic Article
      description: Create topic article.
      operationId: create-topic-article
      x-api-path-slug: topicstopic-idarticles-format-post
      parameters:
      - in: path
        name: format
      - in: path
        name: topic_id
      responses:
        200:
          description: OK
      tags:
      - Topics
      - Topic
      - Articles
      - Format
  /users.{format}:
    get:
      summary: Get Users
      description: Get users.
      operationId: get-users
      x-api-path-slug: users-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Users
      - Format
  /users/{id}.{format}:
    get:
      summary: Get User
      description: Get user.
      operationId: get-user
      x-api-path-slug: usersid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Format
---