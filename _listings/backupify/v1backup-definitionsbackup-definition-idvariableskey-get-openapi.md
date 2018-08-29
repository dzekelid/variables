---
swagger: "2.0"
x-collection-name: Backupify
x-complete: 0
info:
  title: Backupify Retrieve a specific variable by key for the specified backup_definition
  description: You can only retrieve variables for backup_definitions you have access
    to
  version: 1.0.0
host: api.backupify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/backup_definitions/{backup_definition_id}/variables:
    get:
      summary: Retrieve a list of variables for the specified backup_definition
      description: You can only retrieve variables for backup_definitions you have
        access to. Records are returned in ascending order (by id), with a default
        of 20 per page. Links to the next, previous, first, and last pages can be
        found in the response headers.
      operationId: getV1BackupDefinitionsBackupDefinitionVariables
      x-api-path-slug: v1backup-definitionsbackup-definition-idvariables-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_definition_id
        description: ID of the backup_definition to retrieve variables for
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Definitions
      - Backup
      - Definition
      - Id
      - Variables
    post:
      summary: Create a new variable for the specified key for the specified backup_definition
      description: It is only possible to create variables for backup_definitions
        you have permission to manage.
      operationId: postV1BackupDefinitionsBackupDefinitionVariables
      x-api-path-slug: v1backup-definitionsbackup-definition-idvariables-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_definition_id
        description: ID of the backup_definition to create a variable for
      - in: formData
        name: variable[default_value]
        description: A default value that can be used when no instance specific value
          is provided
      - in: formData
        name: variable[description]
        description: Description offering additional information or detail about the
          variable
      - in: formData
        name: variable[key]
        description: The symbolic name or identifier to access the defined variable
          by
      - in: formData
        name: variable[name]
        description: A human-friendly name for the variable
      - in: formData
        name: variable[optional]
        description: Flag indicating whether this variable is optional or if a value
          is required
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Definitions
      - Backup
      - Definition
      - Id
      - Variables
  /v1/backup_definitions/{backup_definition_id}/variables/{key}:
    get:
      summary: Retrieve a specific variable by key for the specified backup_definition
      description: You can only retrieve variables for backup_definitions you have
        access to
      operationId: getV1BackupDefinitionsBackupDefinitionVariablesKey
      x-api-path-slug: v1backup-definitionsbackup-definition-idvariableskey-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_definition_id
        description: ID of the backup_definition to retrieve a variable for
      - in: path
        name: key
        description: The key, symbolic name, or identifier of the variable to retrieve
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Definitions
      - Backup
      - Definition
      - Id
      - Variables
      - Key
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