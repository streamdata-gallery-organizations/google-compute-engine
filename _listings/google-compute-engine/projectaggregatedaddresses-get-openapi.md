---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Get Addresses
  description: Retrieves an aggregated list of addresses.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}:
    get:
      summary: Get Project
      description: Returns the specified Project resource.
      operationId: compute.projects.get
      x-api-path-slug: project-get
      parameters:
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Project
  /{project}/aggregated/addresses:
    get:
      summary: Get Addresses
      description: Retrieves an aggregated list of addresses.
      operationId: compute.addresses.aggregatedList
      x-api-path-slug: projectaggregatedaddresses-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Address
      - Aggregation
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