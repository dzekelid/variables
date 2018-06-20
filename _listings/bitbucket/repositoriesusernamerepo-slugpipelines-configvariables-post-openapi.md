---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Add Repositories Username Repo Slug Pipelines Config Variables
  description: Post repositories username repo slug pipelines config variables
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/pipelines_config/variables/:
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Variables
      description: Get repositories username repo slug pipelines config variables
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigVariables
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariables-get
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
      - Variables
    post:
      summary: Add Repositories Username Repo Slug Pipelines Config Variables
      description: Post repositories username repo slug pipelines config variables
      operationId: postRepositoriesUsernameRepoSlugPipelinesConfigVariables
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariables-post
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The variable to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
      - Variables
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