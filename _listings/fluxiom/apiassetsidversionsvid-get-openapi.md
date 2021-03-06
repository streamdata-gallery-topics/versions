---
swagger: "2.0"
x-collection-name: Fluxiom
x-complete: 0
info:
  title: Fluxiom API Get single asset version
  description: Get single asset version
  termsOfService: http://www.fluxiom.com/terms
  version: v1
host: '{subdomain}.fluxiom.com'
basePath: /api/{format}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/assets/ID/versions:
    get:
      summary: Get asset versions
      description: Get asset versions
      operationId: get-asset-versions
      x-api-path-slug: apiassetsidversions-get
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Versions
    post:
      summary: Create asset version
      description: Create asset version
      operationId: create-asset-version
      x-api-path-slug: apiassetsidversions-post
      parameters:
      - in: query
        name: comment
        description: comment     tt string
      - in: query
        name: file
        description: file        tt postdata
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Versions
  /api/assets/ID/versions/VID:
    get:
      summary: Get single asset version
      description: Get single asset version
      operationId: get-single-asset-version
      x-api-path-slug: apiassetsidversionsvid-get
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Versions
      - VID
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