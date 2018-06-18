---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Job Build
  description: Builds (compiles) the specified job in the specified Data Lake Analytics
    account for job correctness and validation.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /BuildJob:
    post:
      summary: Job Build
      description: Builds (compiles) the specified job in the specified Data Lake
        Analytics account for job correctness and validation.
      operationId: Job_Build
      x-api-path-slug: buildjob-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters to build a job
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Job Build
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