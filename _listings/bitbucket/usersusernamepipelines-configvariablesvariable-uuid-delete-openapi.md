---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Delete Users Username Pipelines Config Variables Variable Uu
  description: Delete users username pipelines config variables variable uu
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
  /repositories/{username}/{repo_slug}/pipelines_config/variables/{variable_uuid}:
    delete:
      summary: Delete Repositories Username Repo Slug Pipelines Config Variables Variable
        Uu
      description: Delete repositories username repo slug pipelines config variables
        variable uu
      operationId: deleteRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariablesvariable-uuid-delete
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to delete
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
      - Variable
      - Uu
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Variables Variable
        Uu
      description: Get repositories username repo slug pipelines config variables
        variable uu
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariablesvariable-uuid-get
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to retrieve
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
      - Variable
      - Uu
    put:
      summary: Update Repositories Username Repo Slug Pipelines Config Variables Variable
        Uu
      description: Put repositories username repo slug pipelines config variables
        variable uu
      operationId: putRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariablesvariable-uuid-put
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to update
      - in: body
        name: _body
        description: The updated variable
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
      - Variable
      - Uu
  /teams/{username}/pipelines_config/variables/:
    get:
      summary: Get Teams Username Pipelines Config Variables
      description: Get teams username pipelines config variables
      operationId: getTeamsUsernamePipelinesConfigVariables
      x-api-path-slug: teamsusernamepipelines-configvariables-get
      parameters:
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
    post:
      summary: Add Teams Username Pipelines Config Variables
      description: Post teams username pipelines config variables
      operationId: postTeamsUsernamePipelinesConfigVariables
      x-api-path-slug: teamsusernamepipelines-configvariables-post
      parameters:
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
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
  /teams/{username}/pipelines_config/variables/{variable_uuid}:
    delete:
      summary: Delete Teams Username Pipelines Config Variables Variable Uu
      description: Delete teams username pipelines config variables variable uu
      operationId: deleteTeamsUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: teamsusernamepipelines-configvariablesvariable-uuid-delete
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to delete
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
    get:
      summary: Get Teams Username Pipelines Config Variables Variable Uu
      description: Get teams username pipelines config variables variable uu
      operationId: getTeamsUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: teamsusernamepipelines-configvariablesvariable-uuid-get
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to retrieve
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
    put:
      summary: Update Teams Username Pipelines Config Variables Variable Uu
      description: Put teams username pipelines config variables variable uu
      operationId: putTeamsUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: teamsusernamepipelines-configvariablesvariable-uuid-put
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable
      - in: body
        name: _body
        description: The updated variable
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
  /users/{username}/pipelines_config/variables/:
    get:
      summary: Get Users Username Pipelines Config Variables
      description: Get users username pipelines config variables
      operationId: getUsersUsernamePipelinesConfigVariables
      x-api-path-slug: usersusernamepipelines-configvariables-get
      parameters:
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
    post:
      summary: Add Users Username Pipelines Config Variables
      description: Post users username pipelines config variables
      operationId: postUsersUsernamePipelinesConfigVariables
      x-api-path-slug: usersusernamepipelines-configvariables-post
      parameters:
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
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
  /users/{username}/pipelines_config/variables/{variable_uuid}:
    delete:
      summary: Delete Users Username Pipelines Config Variables Variable Uu
      description: Delete users username pipelines config variables variable uu
      operationId: deleteUsersUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: usersusernamepipelines-configvariablesvariable-uuid-delete
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
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