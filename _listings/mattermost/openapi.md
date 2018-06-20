---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost API Reference
  description: -api-v4-is-stable-with-the-mattermost-server-4-0-release--api-v3-was-deprecated-on-january-16th-2018-and-scheduled-for-removal-in-mattermost-v5-0--details-heretagapiv3deprecation--looking-for-the-api-v3-reference-it-has-moved-herehttpsapi-mattermost-comv3-
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /config/environment:
    get:
      summary: Get configuration made through environment variables
      description: |-
        Retrieve a json object mirroring the server configuration where fields are set to true
        if the corresponding config setting is set through an environment variable. Settings
        that haven't been set through environment variables will be missing from the object.

        __Minimum server version__: 4.10

        ##### Permissions
        Must have `manage_system` permission.
      operationId: retrieve-a-json-object-mirroring-the-server-configuration-where-fields-are-set-to-trueif-the-corresp
      x-api-path-slug: configenvironment-get
      responses:
        200:
          description: OK
      tags:
      - Configuration
      - Made
      - Through
      - Environment
      - Variables
---