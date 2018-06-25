---
name: Backupify
x-slug: backupify
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Variables
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/apis.md
specificationVersion: "0.14"
apis:
- name: Backupify Retrieve a list of variables for the specified backup_definition
  x-api-slug: backupify
  description: You can only retrieve variables for backup_definitions you have access
    to. Records are returned in ascending order (by id), with a default of 20 per
    page. Links to the next, previous, first, and last pages can be found in the response
    headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_definitions/{backup_definition_id}/variables
  tags: V1,Backup,Definitions,Backup,Definition,Id,Variables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariables-get-openapi.md
- name: Backupify Create a new variable for the specified key for the specified backup_definition
  x-api-slug: backupify
  description: It is only possible to create variables for backup_definitions you
    have permission to manage.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_definitions/{backup_definition_id}/variables
  tags: V1,Backup,Definitions,Backup,Definition,Id,Variables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariables-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariables-post-openapi.md
- name: Backupify Retrieve a specific variable by key for the specified backup_definition
  x-api-slug: backupify
  description: You can only retrieve variables for backup_definitions you have access
    to
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_definitions/{backup_definition_id}/variables/{key}
  tags: V1,Backup,Definitions,Backup,Definition,Id,Variables,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariableskey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariableskey-get-openapi.md
- name: Backupify Update a specific variable by key for the specified backup_definition
  x-api-slug: backupify
  description: You can only update variables for backup_definitions you have access
    to. Additionally, it is not possible to update a variable's key. Requests including
    a modified key name will result in an error.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_definitions/{backup_definition_id}/variables/{key}
  tags: V1,Backup,Definitions,Backup,Definition,Id,Variables,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariableskey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-definitionsbackup-definition-idvariableskey-put-openapi.md
- name: Backupify Retrieve a list of variables for the specified backup_instance
  x-api-slug: backupify
  description: You can only retrieve variables for backup_instances you have access
    to. Records are returned in ascending order (by id), with a default of 20 per
    page. Links to the next, previous, first, and last pages can be found in the response
    headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/variables
  tags: V1,Backup,Instances,Backup,Instance,Id,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-instancesbackup-instance-idvariables-get-openapi.md
- name: Backupify Create a custom variable value for the specified key for the specified
    backup_instance
  x-api-slug: backupify
  description: The key specified must refer to the key of a previously defined backup_definition
    variable. It is only possible to create variables for backup_instances you have
    permission to manage.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/variables
  tags: V1,Backup,Instances,Backup,Instance,Id,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-instancesbackup-instance-idvariables-post-openapi.md
- name: Backupify Retrieve a specific variable by key for the specified backup_instance
  x-api-slug: backupify
  description: You can only retrieve variables for backup_instances you have access
    to
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/variables/{key}
  tags: V1,Backup,Instances,Backup,Instance,Id,Variables,Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-instancesbackup-instance-idvariableskey-get-openapi.md
- name: Backupify Update the value of a variable by key for the specified backup_instance
  x-api-slug: backupify
  description: You can only alter variables for backup_instances you have access to
    manage
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/variables/{key}
  tags: V1,Backup,Instances,Backup,Instance,Id,Variables,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-instancesbackup-instance-idvariableskey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/v1backup-instancesbackup-instance-idvariableskey-put-openapi.md
- name: Backupify
  x-api-slug: backupify
  description: 'Backupify is a backup service for SaaS accounts. Backupify can help
    users backup their SaaS accounts and restore if and when needed. Backupify offers
    a developers program for developers to access and integrate the functionality
    of Backupify with other applications. Public documentation is not available; interested
    developers should sign up here for more information on the developers program:
    https://www.backupify.com/solutions/developers or email developerprogram@backupify.com.'
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/backupify/openapi.md
x-common:
- type: x-blog
  url: https://www.backupify.com/blog
- type: x-website
  url: http://backupify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---