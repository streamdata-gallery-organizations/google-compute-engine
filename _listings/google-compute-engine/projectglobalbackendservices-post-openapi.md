---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Create Backend Service
  description: Creates a BackendService resource in the specified project using the
    data included in the request. There are several restrictions and guidelines to
    keep in mind when creating a backend service. Read  Restrictions and Guidelines
    for more information.
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
  /{project}/aggregated/autoscalers:
    get:
      summary: Get Autoscalers
      description: Retrieves an aggregated list of autoscalers.
      operationId: compute.autoscalers.aggregatedList
      x-api-path-slug: projectaggregatedautoscalers-get
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
      - Autoscaler
      - Aggregation
  /{project}/aggregated/backendServices:
    get:
      summary: Get Backend services
      description: Retrieves the list of all BackendService resources, regional and
        global, available to the specified project.
      operationId: compute.backendServices.aggregatedList
      x-api-path-slug: projectaggregatedbackendservices-get
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
        description: Name of the project scoping this request
      responses:
        200:
          description: OK
      tags:
      - Backend Service
      - Aggregation
  /{project}/aggregated/diskTypes:
    get:
      summary: Get Disk Type
      description: Retrieves an aggregated list of disk types.
      operationId: compute.diskTypes.aggregatedList
      x-api-path-slug: projectaggregateddisktypes-get
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
      - Disk
      - Aggregation
  /{project}/aggregated/disks:
    get:
      summary: Get Disks
      description: Retrieves an aggregated list of persistent disks.
      operationId: compute.disks.aggregatedList
      x-api-path-slug: projectaggregateddisks-get
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
      - Disk
      - Aggregation
  /{project}/aggregated/forwardingRules:
    get:
      summary: Get Forwarding Rules
      description: Retrieves an aggregated list of forwarding rules.
      operationId: compute.forwardingRules.aggregatedList
      x-api-path-slug: projectaggregatedforwardingrules-get
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
      - Forwarding Rules
      - Aggregation
  /{project}/aggregated/instanceGroupManagers:
    get:
      summary: Get Instance Group Managers
      description: Retrieves the list of managed instance groups and groups them by
        zone.
      operationId: compute.instanceGroupManagers.aggregatedList
      x-api-path-slug: projectaggregatedinstancegroupmanagers-get
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
      - Instance Group
  /{project}/aggregated/instanceGroups:
    get:
      summary: Get Instance Groups
      description: Retrieves the list of instance groups and sorts them by zone.
      operationId: compute.instanceGroups.aggregatedList
      x-api-path-slug: projectaggregatedinstancegroups-get
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
      - Instance Group
      - Aggregation
  /{project}/aggregated/instances:
    get:
      summary: Get Instances
      description: Retrieves aggregated list of instances.
      operationId: compute.instances.aggregatedList
      x-api-path-slug: projectaggregatedinstances-get
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
      - Instance
      - Aggregation
  /{project}/aggregated/machineTypes:
    get:
      summary: Get Machine Types
      description: Retrieves an aggregated list of machine types.
      operationId: compute.machineTypes.aggregatedList
      x-api-path-slug: projectaggregatedmachinetypes-get
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
      - Machine
      - Aggregation
  /{project}/aggregated/operations:
    get:
      summary: Get Operations
      description: Retrieves an aggregated list of all operations.
      operationId: compute.globalOperations.aggregatedList
      x-api-path-slug: projectaggregatedoperations-get
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
      - Operation
      - Aggregation
  /{project}/aggregated/routers:
    get:
      summary: Get Routers
      description: Retrieves an aggregated list of routers.
      operationId: compute.routers.aggregatedList
      x-api-path-slug: projectaggregatedrouters-get
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
      - Router
      - Aggregation
  /{project}/aggregated/subnetworks:
    get:
      summary: Get Subnetworks
      description: Retrieves an aggregated list of subnetworks.
      operationId: compute.subnetworks.aggregatedList
      x-api-path-slug: projectaggregatedsubnetworks-get
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
      - Subnetwork
      - Aggregation
  /{project}/aggregated/targetInstances:
    get:
      summary: Get Target Instances
      description: Retrieves an aggregated list of target instances.
      operationId: compute.targetInstances.aggregatedList
      x-api-path-slug: projectaggregatedtargetinstances-get
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
      - Target Instance
      - Aggregation
  /{project}/aggregated/targetPools:
    get:
      summary: Get Target Pools
      description: Retrieves an aggregated list of target pools.
      operationId: compute.targetPools.aggregatedList
      x-api-path-slug: projectaggregatedtargetpools-get
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
      - Target Pools
      - Aggregation
  /{project}/aggregated/targetVpnGateways:
    get:
      summary: Get Target VPN Gateways
      description: Retrieves an aggregated list of target VPN gateways.
      operationId: compute.targetVpnGateways.aggregatedList
      x-api-path-slug: projectaggregatedtargetvpngateways-get
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
      - Target VPN Gateway
      - Aggregation
  /{project}/aggregated/vpnTunnels:
    get:
      summary: Get VPN Tunnels
      description: Retrieves an aggregated list of VPN tunnels.
      operationId: compute.vpnTunnels.aggregatedList
      x-api-path-slug: projectaggregatedvpntunnels-get
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
      - VPN Tunnel
  /{project}/global/addresses:
    get:
      summary: Get Global Addreses
      description: Retrieves a list of global addresses.
      operationId: compute.globalAddresses.list
      x-api-path-slug: projectglobaladdresses-get
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
    post:
      summary: Add Address
      description: Creates an address resource in the specified project using the
        data included in the request.
      operationId: compute.globalAddresses.insert
      x-api-path-slug: projectglobaladdresses-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Address
  /{project}/global/addresses/{address}:
    delete:
      summary: Delete Address
      description: Deletes the specified address resource.
      operationId: compute.globalAddresses.delete
      x-api-path-slug: projectglobaladdressesaddress-delete
      parameters:
      - in: path
        name: address
        description: Name of the address resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Address
    get:
      summary: Get Address
      description: Returns the specified address resource. Get a list of available
        addresses by making a list() request.
      operationId: compute.globalAddresses.get
      x-api-path-slug: projectglobaladdressesaddress-get
      parameters:
      - in: path
        name: address
        description: Name of the address resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Address
  /{project}/global/backendBuckets:
    get:
      summary: Get Backend Buckets
      description: Retrieves the list of BackendBucket resources available to the
        specified project.
      operationId: compute.backendBuckets.list
      x-api-path-slug: projectglobalbackendbuckets-get
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
      - Backend Bucket
    post:
      summary: Create Backend Buckets
      description: Creates a BackendBucket resource in the specified project using
        the data included in the request.
      operationId: compute.backendBuckets.insert
      x-api-path-slug: projectglobalbackendbuckets-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Bucket
  /{project}/global/backendBuckets/{backendBucket}:
    delete:
      summary: Delete Backend Bucket
      description: Deletes the specified BackendBucket resource.
      operationId: compute.backendBuckets.delete
      x-api-path-slug: projectglobalbackendbucketsbackendbucket-delete
      parameters:
      - in: path
        name: backendBucket
        description: Name of the BackendBucket resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Bucket
    get:
      summary: Create Backend Bucket
      description: Returns the specified BackendBucket resource. Get a list of available
        backend buckets by making a list() request.
      operationId: compute.backendBuckets.get
      x-api-path-slug: projectglobalbackendbucketsbackendbucket-get
      parameters:
      - in: path
        name: backendBucket
        description: Name of the BackendBucket resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Bucket
    patch:
      summary: Update Backend Bucket
      description: Updates the specified BackendBucket resource with the data included
        in the request. This method supports patch semantics.
      operationId: compute.backendBuckets.patch
      x-api-path-slug: projectglobalbackendbucketsbackendbucket-patch
      parameters:
      - in: path
        name: backendBucket
        description: Name of the BackendBucket resource to update
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Bucket
    put:
      summary: Update Backend Bucket
      description: Updates the specified BackendBucket resource with the data included
        in the request.
      operationId: compute.backendBuckets.update
      x-api-path-slug: projectglobalbackendbucketsbackendbucket-put
      parameters:
      - in: path
        name: backendBucket
        description: Name of the BackendBucket resource to update
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Bucket
  /{project}/global/backendServices:
    get:
      summary: Get Backend Services
      description: Retrieves the list of BackendService resources available to the
        specified project.
      operationId: compute.backendServices.list
      x-api-path-slug: projectglobalbackendservices-get
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
      - Backend Service
    post:
      summary: Create Backend Service
      description: Creates a BackendService resource in the specified project using
        the data included in the request. There are several restrictions and guidelines
        to keep in mind when creating a backend service. Read  Restrictions and Guidelines
        for more information.
      operationId: compute.backendServices.insert
      x-api-path-slug: projectglobalbackendservices-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Service
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