---
name: Heroku
x-slug: heroku
description: Heroku is a platform as a service (PaaS) that enables developers to build,
  run, and operate applications entirely in the cloud.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
x-kinRank: "8"
x-alexaRank: "6044"
tags: Variables
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/apis.md
specificationVersion: "0.14"
apis:
- name: Heroku Parameters Application Config Variables
  x-api-slug: heroku
  description: Parameters application config variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/config_vars
  tags: Parameters, Application, Config, Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-vars-parameters-openapi.md
- name: Heroku Get Application Config Variables
  x-api-slug: heroku
  description: Get application config variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/config_vars
  tags: Application, Config, Variables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-vars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-vars-get-openapi.md
- name: Heroku Put Application Config Variables
  x-api-slug: heroku
  description: Put application config variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/config_vars
  tags: Put, Application, Config, Variables
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-vars-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-vars-put-openapi.md
- name: Heroku Parameters Application Config Variables Key
  x-api-slug: heroku
  description: Parameters application config variables key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/config_vars/{key}
  tags: Parameters, Application, Config, Variables, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-varskey-parameters-openapi.md
- name: Heroku Delete Application Config Variables Key
  x-api-slug: heroku
  description: Delete application config variables key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/config_vars/{key}
  tags: Application, Config, Variables, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-varskey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/appsappconfig-varskey-delete-openapi.md
- name: Heroku
  x-api-slug: heroku
  description: Learn about building, deploying and managing your apps on Heroku.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com//
  tags: Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/variables/master/_listings/heroku/openapi.md
x-common:
- type: x-base
  url: https://api.heroku.com
- type: x-blog
  url: https://blog.heroku.com/
- type: x-blog-rss
  url: http://feeds2.feedburner.com/heroku
- type: x-command-line-interface
  url: https://devcenter.heroku.com/articles/heroku-command
- type: x-crunchbase
  url: https://crunchbase.com/organization/heroku
- type: x-crunchbase
  url: http://www.crunchbase.com/company/heroku
- type: x-developer
  url: https://devcenter.heroku.com/
- type: x-email
  url: pr@heroku.com
- type: x-email
  url: abuse@heroku.com
- type: x-email
  url: feedback@heroku.com
- type: x-getting-started
  url: https://devcenter.heroku.com/start
- type: x-github
  url: https://github.com/heroku
- type: x-issues
  url: https://status.heroku.com/incidents
- type: x-java-library
  url: https://devcenter.heroku.com/categories/java
- type: x-node-js
  url: https://devcenter.heroku.com/categories/nodejs
- type: x-php-library
  url: https://devcenter.heroku.com/categories/php
- type: x-pricing
  url: https://www.heroku.com/pricing
- type: x-privacy
  url: https://www.heroku.com/policy/privacy
- type: x-python-library
  url: https://devcenter.heroku.com/categories/python
- type: x-ruby-library
  url: https://devcenter.heroku.com/categories/ruby
- type: x-security
  url: https://www.heroku.com/policy/security
- type: x-selfservice-registration
  url: https://signup.heroku.com/dc
- type: x-support
  url: https://www.heroku.com/support
- type: x-terms-of-service
  url: https://www.heroku.com/policy/tos
- type: x-twitter
  url: https://twitter.com/heroku
- type: x-twitter
  url: https://twitter.com/HerokuDevCenter
- type: x-website
  url: http://heroku.com
- type: x-website
  url: https://www.heroku.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---