---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Update HTTPS Health Check
  description: Updates a HttpsHealthCheck resource in the specified project using
    the data included in the request. This method supports patch semantics.
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
  /{project}/global/backendServices/{backendService}:
    delete:
      summary: Delete Backend Service
      description: Deletes the specified BackendService resource.
      operationId: compute.backendServices.delete
      x-api-path-slug: projectglobalbackendservicesbackendservice-delete
      parameters:
      - in: path
        name: backendService
        description: Name of the BackendService resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Service
    get:
      summary: Get Backend Service
      description: Returns the specified BackendService resource. Get a list of available
        backend services by making a list() request.
      operationId: compute.backendServices.get
      x-api-path-slug: projectglobalbackendservicesbackendservice-get
      parameters:
      - in: path
        name: backendService
        description: Name of the BackendService resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Backend Service
    patch:
      summary: Update Backend Service
      description: Updates the specified BackendService resource with the data included
        in the request. There are several restrictions and guidelines to keep in mind
        when updating a backend service. Read  Restrictions and Guidelines for more
        information. This method supports patch semantics.
      operationId: compute.backendServices.patch
      x-api-path-slug: projectglobalbackendservicesbackendservice-patch
      parameters:
      - in: path
        name: backendService
        description: Name of the BackendService resource to update
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
    put:
      summary: Update Backend Service
      description: Updates the specified BackendService resource with the data included
        in the request. There are several restrictions and guidelines to keep in mind
        when updating a backend service. Read  Restrictions and Guidelines for more
        information.
      operationId: compute.backendServices.update
      x-api-path-slug: projectglobalbackendservicesbackendservice-put
      parameters:
      - in: path
        name: backendService
        description: Name of the BackendService resource to update
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
  /{project}/global/backendServices/{backendService}/getHealth:
    post:
      summary: Get Backend Service Health Check
      description: Gets the most recent health check results for this BackendService.
      operationId: compute.backendServices.getHealth
      x-api-path-slug: projectglobalbackendservicesbackendservicegethealth-post
      parameters:
      - in: path
        name: backendService
        description: Name of the BackendService resource to which the queried instance
          belongs
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
      responses:
        200:
          description: OK
      tags:
      - Backend Service
  /{project}/global/firewalls:
    get:
      summary: Get Firewalls
      description: Retrieves the list of firewall rules available to the specified
        project.
      operationId: compute.firewalls.list
      x-api-path-slug: projectglobalfirewalls-get
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
      - Firewall
    post:
      summary: Create Firewall
      description: Creates a firewall rule in the specified project using the data
        included in the request.
      operationId: compute.firewalls.insert
      x-api-path-slug: projectglobalfirewalls-post
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
      - Firewall
  /{project}/global/firewalls/{firewall}:
    delete:
      summary: Delete Firewall
      description: Deletes the specified firewall.
      operationId: compute.firewalls.delete
      x-api-path-slug: projectglobalfirewallsfirewall-delete
      parameters:
      - in: path
        name: firewall
        description: Name of the firewall rule to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Firewall
    get:
      summary: Get Firewall
      description: Returns the specified firewall.
      operationId: compute.firewalls.get
      x-api-path-slug: projectglobalfirewallsfirewall-get
      parameters:
      - in: path
        name: firewall
        description: Name of the firewall rule to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Firewall
    patch:
      summary: Update Firewall
      description: Updates the specified firewall rule with the data included in the
        request. This method supports patch semantics.
      operationId: compute.firewalls.patch
      x-api-path-slug: projectglobalfirewallsfirewall-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: firewall
        description: Name of the firewall rule to update
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Firewall
    put:
      summary: Update Firewall
      description: Updates the specified firewall rule with the data included in the
        request.
      operationId: compute.firewalls.update
      x-api-path-slug: projectglobalfirewallsfirewall-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: firewall
        description: Name of the firewall rule to update
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Firewall
  /{project}/global/forwardingRules:
    get:
      summary: Get Forwarding Rules
      description: Retrieves a list of ForwardingRule resources available to the specified
        project.
      operationId: compute.globalForwardingRules.list
      x-api-path-slug: projectglobalforwardingrules-get
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
      - Forward Rule
    post:
      summary: Create Forwarding Rule
      description: Creates a ForwardingRule resource in the specified project and
        region using the data included in the request.
      operationId: compute.globalForwardingRules.insert
      x-api-path-slug: projectglobalforwardingrules-post
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
      - Forward Rule
  /{project}/global/forwardingRules/{forwardingRule}:
    delete:
      summary: Delete Forwarding Rule
      description: Deletes the specified ForwardingRule resource.
      operationId: compute.globalForwardingRules.delete
      x-api-path-slug: projectglobalforwardingrulesforwardingrule-delete
      parameters:
      - in: path
        name: forwardingRule
        description: Name of the ForwardingRule resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Forward Rule
    get:
      summary: Get Forwarding Rule
      description: Returns the specified ForwardingRule resource. Get a list of available
        forwarding rules by making a list() request.
      operationId: compute.globalForwardingRules.get
      x-api-path-slug: projectglobalforwardingrulesforwardingrule-get
      parameters:
      - in: path
        name: forwardingRule
        description: Name of the ForwardingRule resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Forward Rule
  /{project}/global/forwardingRules/{forwardingRule}/setTarget:
    post:
      summary: Update Forwarding Rule
      description: Changes target URL for forwarding rule. The new target should be
        of the same type as the old target.
      operationId: compute.globalForwardingRules.setTarget
      x-api-path-slug: projectglobalforwardingrulesforwardingrulesettarget-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: forwardingRule
        description: Name of the ForwardingRule resource in which target is to be
          set
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Forward Rule
  /{project}/global/healthChecks:
    get:
      summary: Get Health Checks
      description: Retrieves the list of HealthCheck resources available to the specified
        project.
      operationId: compute.healthChecks.list
      x-api-path-slug: projectglobalhealthchecks-get
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
      - Checks
      - Health
    post:
      summary: Create Health Check
      description: Creates a HealthCheck resource in the specified project using the
        data included in the request.
      operationId: compute.healthChecks.insert
      x-api-path-slug: projectglobalhealthchecks-post
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
      - Checks
      - Health
  /{project}/global/healthChecks/{healthCheck}:
    delete:
      summary: Delete Health Check
      description: Deletes the specified HealthCheck resource.
      operationId: compute.healthChecks.delete
      x-api-path-slug: projectglobalhealthcheckshealthcheck-delete
      parameters:
      - in: path
        name: healthCheck
        description: Name of the HealthCheck resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    get:
      summary: Get Health Check
      description: Returns the specified HealthCheck resource. Get a list of available
        health checks by making a list() request.
      operationId: compute.healthChecks.get
      x-api-path-slug: projectglobalhealthcheckshealthcheck-get
      parameters:
      - in: path
        name: healthCheck
        description: Name of the HealthCheck resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    patch:
      summary: Update Health Check
      description: Updates a HealthCheck resource in the specified project using the
        data included in the request. This method supports patch semantics.
      operationId: compute.healthChecks.patch
      x-api-path-slug: projectglobalhealthcheckshealthcheck-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: healthCheck
        description: Name of the HealthCheck resource to update
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    put:
      summary: Update Health Check
      description: Updates a HealthCheck resource in the specified project using the
        data included in the request.
      operationId: compute.healthChecks.update
      x-api-path-slug: projectglobalhealthcheckshealthcheck-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: healthCheck
        description: Name of the HealthCheck resource to update
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
  /{project}/global/httpHealthChecks:
    get:
      summary: Get HTTP Health Checks
      description: Retrieves the list of HttpHealthCheck resources available to the
        specified project.
      operationId: compute.httpHealthChecks.list
      x-api-path-slug: projectglobalhttphealthchecks-get
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
      - Checks
      - Health
    post:
      summary: Create HTTP Health Check
      description: Creates a HttpHealthCheck resource in the specified project using
        the data included in the request.
      operationId: compute.httpHealthChecks.insert
      x-api-path-slug: projectglobalhttphealthchecks-post
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
      - Checks
      - Health
  /{project}/global/httpHealthChecks/{httpHealthCheck}:
    delete:
      summary: Delete HTTP Health Check
      description: Deletes the specified HttpHealthCheck resource.
      operationId: compute.httpHealthChecks.delete
      x-api-path-slug: projectglobalhttphealthcheckshttphealthcheck-delete
      parameters:
      - in: path
        name: httpHealthCheck
        description: Name of the HttpHealthCheck resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    get:
      summary: Create HTTP Health Check
      description: Returns the specified HttpHealthCheck resource. Get a list of available
        HTTP health checks by making a list() request.
      operationId: compute.httpHealthChecks.get
      x-api-path-slug: projectglobalhttphealthcheckshttphealthcheck-get
      parameters:
      - in: path
        name: httpHealthCheck
        description: Name of the HttpHealthCheck resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    patch:
      summary: Update HTTP Health Check
      description: Updates a HttpHealthCheck resource in the specified project using
        the data included in the request. This method supports patch semantics.
      operationId: compute.httpHealthChecks.patch
      x-api-path-slug: projectglobalhttphealthcheckshttphealthcheck-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: httpHealthCheck
        description: Name of the HttpHealthCheck resource to update
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    put:
      summary: Update HTTP Health Check
      description: Updates a HttpHealthCheck resource in the specified project using
        the data included in the request.
      operationId: compute.httpHealthChecks.update
      x-api-path-slug: projectglobalhttphealthcheckshttphealthcheck-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: httpHealthCheck
        description: Name of the HttpHealthCheck resource to update
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
  /{project}/global/httpsHealthChecks:
    get:
      summary: Get HTTPS Health Checks
      description: Retrieves the list of HttpsHealthCheck resources available to the
        specified project.
      operationId: compute.httpsHealthChecks.list
      x-api-path-slug: projectglobalhttpshealthchecks-get
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
      - Checks
      - Health
    post:
      summary: Create HTTPS Health Check
      description: Creates a HttpsHealthCheck resource in the specified project using
        the data included in the request.
      operationId: compute.httpsHealthChecks.insert
      x-api-path-slug: projectglobalhttpshealthchecks-post
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
      - Checks
      - Health
  /{project}/global/httpsHealthChecks/{httpsHealthCheck}:
    delete:
      summary: Delete HTTPS Health Check
      description: Deletes the specified HttpsHealthCheck resource.
      operationId: compute.httpsHealthChecks.delete
      x-api-path-slug: projectglobalhttpshealthcheckshttpshealthcheck-delete
      parameters:
      - in: path
        name: httpsHealthCheck
        description: Name of the HttpsHealthCheck resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    get:
      summary: Get HTTPS Health Check
      description: Returns the specified HttpsHealthCheck resource. Get a list of
        available HTTPS health checks by making a list() request.
      operationId: compute.httpsHealthChecks.get
      x-api-path-slug: projectglobalhttpshealthcheckshttpshealthcheck-get
      parameters:
      - in: path
        name: httpsHealthCheck
        description: Name of the HttpsHealthCheck resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
    patch:
      summary: Update HTTPS Health Check
      description: Updates a HttpsHealthCheck resource in the specified project using
        the data included in the request. This method supports patch semantics.
      operationId: compute.httpsHealthChecks.patch
      x-api-path-slug: projectglobalhttpshealthcheckshttpshealthcheck-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: httpsHealthCheck
        description: Name of the HttpsHealthCheck resource to update
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
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