---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 1
info:
  title: DataLakeAnalyticsJobManagementClient
  description: creates-an-azure-data-lake-analytics-job-client-
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
---