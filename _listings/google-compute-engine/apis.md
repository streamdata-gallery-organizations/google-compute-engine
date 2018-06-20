---
name: Google Compute Engine
x-slug: google-compute-engine
description: Google Compute Engine delivers virtual machines running in Googles innovative
  data centers and worldwide fiber network. Compute Engines tooling and workflow support
  enable scaling from single instances to global, load-balanced cloud computing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Compute Engine
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google Compute Engine API Get Project
  x-api-slug: google-compute-engine-api
  description: Returns the specified Project resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}
  tags: Project
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/project-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/project-get-openapi.md
- name: Google Compute Engine API Get Addresses
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/addresses
  tags: Address,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedaddresses-get-openapi.md
- name: Google Compute Engine API Get Autoscalers
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of autoscalers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/autoscalers
  tags: Autoscaler,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedautoscalers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedautoscalers-get-openapi.md
- name: Google Compute Engine API Get Backend services
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of all BackendService resources, regional and global,
    available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/backendServices
  tags: Backend Service,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedbackendservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedbackendservices-get-openapi.md
- name: Google Compute Engine API Get Disk Type
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of disk types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/diskTypes
  tags: Disk,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregateddisktypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregateddisktypes-get-openapi.md
- name: Google Compute Engine API Get Disks
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of persistent disks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/disks
  tags: Disk,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregateddisks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregateddisks-get-openapi.md
- name: Google Compute Engine API Get Forwarding Rules
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of forwarding rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/forwardingRules
  tags: Forwarding Rules,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedforwardingrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedforwardingrules-get-openapi.md
- name: Google Compute Engine API Get Instance Group Managers
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of managed instance groups and groups them by zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/instanceGroupManagers
  tags: Instance Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedinstancegroupmanagers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedinstancegroupmanagers-get-openapi.md
- name: Google Compute Engine API Get Instance Groups
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of instance groups and sorts them by zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/instanceGroups
  tags: Instance Group,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedinstancegroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedinstancegroups-get-openapi.md
- name: Google Compute Engine API Get Instances
  x-api-slug: google-compute-engine-api
  description: Retrieves aggregated list of instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/instances
  tags: Instance,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedinstances-get-openapi.md
- name: Google Compute Engine API Get Machine Types
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of machine types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/machineTypes
  tags: Machine,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedmachinetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedmachinetypes-get-openapi.md
- name: Google Compute Engine API Get Operations
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of all operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/operations
  tags: Operation,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedoperations-get-openapi.md
- name: Google Compute Engine API Get Routers
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of routers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/routers
  tags: Router,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedrouters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedrouters-get-openapi.md
- name: Google Compute Engine API Get Subnetworks
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of subnetworks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/subnetworks
  tags: Subnetwork,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedsubnetworks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedsubnetworks-get-openapi.md
- name: Google Compute Engine API Get Target Instances
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of target instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/targetInstances
  tags: Target Instance,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedtargetinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedtargetinstances-get-openapi.md
- name: Google Compute Engine API Get Target Pools
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of target pools.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/targetPools
  tags: Target Pools,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedtargetpools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedtargetpools-get-openapi.md
- name: Google Compute Engine API Get Target VPN Gateways
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of target VPN gateways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/targetVpnGateways
  tags: Target VPN Gateway,Aggregation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedtargetvpngateways-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedtargetvpngateways-get-openapi.md
- name: Google Compute Engine API Get VPN Tunnels
  x-api-slug: google-compute-engine-api
  description: Retrieves an aggregated list of VPN tunnels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/aggregated/vpnTunnels
  tags: VPN Tunnel
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedvpntunnels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectaggregatedvpntunnels-get-openapi.md
- name: Google Compute Engine API Get Global Addreses
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of global addresses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses
  tags: Address
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaladdresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaladdresses-get-openapi.md
- name: Google Compute Engine API Add Address
  x-api-slug: google-compute-engine-api
  description: Creates an address resource in the specified project using the data
    included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaladdresses-post-openapi.md
- name: Google Compute Engine API Delete Address
  x-api-slug: google-compute-engine-api
  description: Deletes the specified address resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses/{address}
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaladdressesaddress-delete-openapi.md
- name: Google Compute Engine API Get Address
  x-api-slug: google-compute-engine-api
  description: Returns the specified address resource. Get a list of available addresses
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/addresses/{address}
  tags: Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaladdressesaddress-get-openapi.md
- name: Google Compute Engine API Get Backend Buckets
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of BackendBucket resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendBuckets
  tags: Backend Bucket
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendbuckets-get-openapi.md
- name: Google Compute Engine API Create Backend Buckets
  x-api-slug: google-compute-engine-api
  description: Creates a BackendBucket resource in the specified project using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendBuckets
  tags: Backend Bucket
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendbuckets-post-openapi.md
- name: Google Compute Engine API Delete Backend Bucket
  x-api-slug: google-compute-engine-api
  description: Deletes the specified BackendBucket resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendBuckets/{backendBucket}
  tags: Backend Bucket
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendbucketsbackendbucket-delete-openapi.md
- name: Google Compute Engine API Create Backend Bucket
  x-api-slug: google-compute-engine-api
  description: Returns the specified BackendBucket resource. Get a list of available
    backend buckets by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendBuckets/{backendBucket}
  tags: Backend Bucket
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendbucketsbackendbucket-get-openapi.md
- name: Google Compute Engine API Update Backend Bucket
  x-api-slug: google-compute-engine-api
  description: Updates the specified BackendBucket resource with the data included
    in the request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendBuckets/{backendBucket}
  tags: Backend Bucket
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendbucketsbackendbucket-patch-openapi.md
- name: Google Compute Engine API Update Backend Bucket
  x-api-slug: google-compute-engine-api
  description: Updates the specified BackendBucket resource with the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendBuckets/{backendBucket}
  tags: Backend Bucket
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendbucketsbackendbucket-put-openapi.md
- name: Google Compute Engine API Get Backend Services
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of BackendService resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendServices
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendservices-get-openapi.md
- name: Google Compute Engine API Create Backend Service
  x-api-slug: google-compute-engine-api
  description: Creates a BackendService resource in the specified project using the
    data included in the request. There are several restrictions and guidelines to
    keep in mind when creating a backend service. Read  Restrictions and Guidelines
    for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendServices
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendservices-post-openapi.md
- name: Google Compute Engine API Delete Backend Service
  x-api-slug: google-compute-engine-api
  description: Deletes the specified BackendService resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendservicesbackendservice-delete-openapi.md
- name: Google Compute Engine API Get Backend Service
  x-api-slug: google-compute-engine-api
  description: Returns the specified BackendService resource. Get a list of available
    backend services by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendservicesbackendservice-get-openapi.md
- name: Google Compute Engine API Update Backend Service
  x-api-slug: google-compute-engine-api
  description: Updates the specified BackendService resource with the data included
    in the request. There are several restrictions and guidelines to keep in mind
    when updating a backend service. Read  Restrictions and Guidelines for more information.
    This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendservicesbackendservice-patch-openapi.md
- name: Google Compute Engine API Update Backend Service
  x-api-slug: google-compute-engine-api
  description: Updates the specified BackendService resource with the data included
    in the request. There are several restrictions and guidelines to keep in mind
    when updating a backend service. Read  Restrictions and Guidelines for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendservicesbackendservice-put-openapi.md
- name: Google Compute Engine API Get Backend Service Health Check
  x-api-slug: google-compute-engine-api
  description: Gets the most recent health check results for this BackendService.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/backendServices/{backendService}/getHealth
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalbackendservicesbackendservicegethealth-post-openapi.md
- name: Google Compute Engine API Get Firewalls
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of firewall rules available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/firewalls
  tags: Firewall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalfirewalls-get-openapi.md
- name: Google Compute Engine API Create Firewall
  x-api-slug: google-compute-engine-api
  description: Creates a firewall rule in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/firewalls
  tags: Firewall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalfirewalls-post-openapi.md
- name: Google Compute Engine API Delete Firewall
  x-api-slug: google-compute-engine-api
  description: Deletes the specified firewall.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/firewalls/{firewall}
  tags: Firewall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalfirewallsfirewall-delete-openapi.md
- name: Google Compute Engine API Get Firewall
  x-api-slug: google-compute-engine-api
  description: Returns the specified firewall.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/firewalls/{firewall}
  tags: Firewall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalfirewallsfirewall-get-openapi.md
- name: Google Compute Engine API Update Firewall
  x-api-slug: google-compute-engine-api
  description: Updates the specified firewall rule with the data included in the request.
    This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/firewalls/{firewall}
  tags: Firewall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalfirewallsfirewall-patch-openapi.md
- name: Google Compute Engine API Update Firewall
  x-api-slug: google-compute-engine-api
  description: Updates the specified firewall rule with the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/firewalls/{firewall}
  tags: Firewall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalfirewallsfirewall-put-openapi.md
- name: Google Compute Engine API Get Forwarding Rules
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of ForwardingRule resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/forwardingRules
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalforwardingrules-get-openapi.md
- name: Google Compute Engine API Create Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Creates a ForwardingRule resource in the specified project and region
    using the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/forwardingRules
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalforwardingrules-post-openapi.md
- name: Google Compute Engine API Delete Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Deletes the specified ForwardingRule resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/forwardingRules/{forwardingRule}
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalforwardingrulesforwardingrule-delete-openapi.md
- name: Google Compute Engine API Get Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Returns the specified ForwardingRule resource. Get a list of available
    forwarding rules by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/forwardingRules/{forwardingRule}
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalforwardingrulesforwardingrule-get-openapi.md
- name: Google Compute Engine API Update Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Changes target URL for forwarding rule. The new target should be of
    the same type as the old target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/forwardingRules/{forwardingRule}/setTarget
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalforwardingrulesforwardingrulesettarget-post-openapi.md
- name: Google Compute Engine API Get Health Checks
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of HealthCheck resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/healthChecks
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthchecks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthchecks-get-openapi.md
- name: Google Compute Engine API Create Health Check
  x-api-slug: google-compute-engine-api
  description: Creates a HealthCheck resource in the specified project using the data
    included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/healthChecks
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthchecks-post-openapi.md
- name: Google Compute Engine API Delete Health Check
  x-api-slug: google-compute-engine-api
  description: Deletes the specified HealthCheck resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/healthChecks/{healthCheck}
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthcheckshealthcheck-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthcheckshealthcheck-delete-openapi.md
- name: Google Compute Engine API Get Health Check
  x-api-slug: google-compute-engine-api
  description: Returns the specified HealthCheck resource. Get a list of available
    health checks by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/healthChecks/{healthCheck}
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthcheckshealthcheck-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthcheckshealthcheck-get-openapi.md
- name: Google Compute Engine API Update Health Check
  x-api-slug: google-compute-engine-api
  description: Updates a HealthCheck resource in the specified project using the data
    included in the request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/healthChecks/{healthCheck}
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthcheckshealthcheck-patch-openapi.md
- name: Google Compute Engine API Update Health Check
  x-api-slug: google-compute-engine-api
  description: Updates a HealthCheck resource in the specified project using the data
    included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/healthChecks/{healthCheck}
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhealthcheckshealthcheck-put-openapi.md
- name: Google Compute Engine API Get HTTP Health Checks
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of HttpHealthCheck resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpHealthChecks
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthchecks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthchecks-get-openapi.md
- name: Google Compute Engine API Create HTTP Health Check
  x-api-slug: google-compute-engine-api
  description: Creates a HttpHealthCheck resource in the specified project using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpHealthChecks
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthchecks-post-openapi.md
- name: Google Compute Engine API Delete HTTP Health Check
  x-api-slug: google-compute-engine-api
  description: Deletes the specified HttpHealthCheck resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpHealthChecks/{httpHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthcheckshttphealthcheck-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthcheckshttphealthcheck-delete-openapi.md
- name: Google Compute Engine API Create HTTP Health Check
  x-api-slug: google-compute-engine-api
  description: Returns the specified HttpHealthCheck resource. Get a list of available
    HTTP health checks by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpHealthChecks/{httpHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthcheckshttphealthcheck-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthcheckshttphealthcheck-get-openapi.md
- name: Google Compute Engine API Update HTTP Health Check
  x-api-slug: google-compute-engine-api
  description: Updates a HttpHealthCheck resource in the specified project using the
    data included in the request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpHealthChecks/{httpHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthcheckshttphealthcheck-patch-openapi.md
- name: Google Compute Engine API Update HTTP Health Check
  x-api-slug: google-compute-engine-api
  description: Updates a HttpHealthCheck resource in the specified project using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpHealthChecks/{httpHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttphealthcheckshttphealthcheck-put-openapi.md
- name: Google Compute Engine API Get HTTPS Health Checks
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of HttpsHealthCheck resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpsHealthChecks
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthchecks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthchecks-get-openapi.md
- name: Google Compute Engine API Create HTTPS Health Check
  x-api-slug: google-compute-engine-api
  description: Creates a HttpsHealthCheck resource in the specified project using
    the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpsHealthChecks
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthchecks-post-openapi.md
- name: Google Compute Engine API Delete HTTPS Health Check
  x-api-slug: google-compute-engine-api
  description: Deletes the specified HttpsHealthCheck resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpsHealthChecks/{httpsHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthcheckshttpshealthcheck-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthcheckshttpshealthcheck-delete-openapi.md
- name: Google Compute Engine API Get HTTPS Health Check
  x-api-slug: google-compute-engine-api
  description: Returns the specified HttpsHealthCheck resource. Get a list of available
    HTTPS health checks by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpsHealthChecks/{httpsHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthcheckshttpshealthcheck-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthcheckshttpshealthcheck-get-openapi.md
- name: Google Compute Engine API Update HTTPS Health Check
  x-api-slug: google-compute-engine-api
  description: Updates a HttpsHealthCheck resource in the specified project using
    the data included in the request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpsHealthChecks/{httpsHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthcheckshttpshealthcheck-patch-openapi.md
- name: Google Compute Engine API Update HTTPS Health Check
  x-api-slug: google-compute-engine-api
  description: Updates a HttpsHealthCheck resource in the specified project using
    the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/httpsHealthChecks/{httpsHealthCheck}
  tags: Checks,Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalhttpshealthcheckshttpshealthcheck-put-openapi.md
- name: Google Compute Engine API Get Images
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of private images available to the specified project.
    Private images are images you create that belong to your project. This method
    does not get any images that belong to other projects, including publicly-available
    images, like Debian 8. If you want to get a list of publicly-available images,
    use this method to make a request to the respective image project, such as debian-cloud
    or windows-cloud.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/images
  tags: Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalimages-get-openapi.md
- name: Google Compute Engine API Create Image
  x-api-slug: google-compute-engine-api
  description: Creates an image in the specified project using the data included in
    the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/images
  tags: Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalimages-post-openapi.md
- name: Google Compute Engine API Create Image Family
  x-api-slug: google-compute-engine-api
  description: Returns the latest image that is part of an image family and is not
    deprecated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/images/family/{family}
  tags: Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalimagesfamilyfamily-get-openapi.md
- name: Google Compute Engine API Delete Image
  x-api-slug: google-compute-engine-api
  description: Deletes the specified image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/images/{image}
  tags: Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalimagesimage-delete-openapi.md
- name: Google Compute Engine API Get Image
  x-api-slug: google-compute-engine-api
  description: Returns the specified image. Get a list of available images by making
    a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/images/{image}
  tags: Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalimagesimage-get-openapi.md
- name: Google Compute Engine API Deprecate Image
  x-api-slug: google-compute-engine-api
  description: |-
    Sets the deprecation status of an image.

    If an empty request body is given, clears the deprecation status instead.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/images/{image}/deprecate
  tags: Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalimagesimagedeprecate-post-openapi.md
- name: Google Compute Engine API Get Instance Templates
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of instance templates that are contained within the
    specified project and zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/instanceTemplates
  tags: Instance Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalinstancetemplates-get-openapi.md
- name: Google Compute Engine API Create Instance Template
  x-api-slug: google-compute-engine-api
  description: Creates an instance template in the specified project using the data
    that is included in the request. If you are creating a new template to update
    an existing instance group, your new instance template must use the same network
    or, if applicable, the same subnetwork as the original template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/instanceTemplates
  tags: Instance Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalinstancetemplates-post-openapi.md
- name: Google Compute Engine API Delete Instance Templates
  x-api-slug: google-compute-engine-api
  description: Deletes the specified instance template. If you delete an instance
    template that is being referenced from another instance group, the instance group
    will not be able to create or recreate virtual machine instances. Deleting an
    instance template is permanent and cannot be undone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/instanceTemplates/{instanceTemplate}
  tags: Instance Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalinstancetemplatesinstancetemplate-delete-openapi.md
- name: Google Compute Engine API Get Instance Template
  x-api-slug: google-compute-engine-api
  description: Returns the specified instance template. Get a list of available instance
    templates by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/instanceTemplates/{instanceTemplate}
  tags: Instance Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalinstancetemplatesinstancetemplate-get-openapi.md
- name: Google Compute Engine API Get License
  x-api-slug: google-compute-engine-api
  description: Returns the specified License resource. Get a list of available licenses
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/licenses/{license}
  tags: License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectgloballicenseslicense-get-openapi.md
- name: Google Compute Engine API Get Networks
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of networks available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/networks
  tags: Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalnetworks-get-openapi.md
- name: Google Compute Engine API Create Network
  x-api-slug: google-compute-engine-api
  description: Creates a network in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/networks
  tags: Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalnetworks-post-openapi.md
- name: Google Compute Engine API Delete Network
  x-api-slug: google-compute-engine-api
  description: Deletes the specified network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/networks/{network}
  tags: Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalnetworksnetwork-delete-openapi.md
- name: Google Compute Engine API Get Network
  x-api-slug: google-compute-engine-api
  description: Returns the specified network. Get a list of available networks by
    making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/networks/{network}
  tags: Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalnetworksnetwork-get-openapi.md
- name: Google Compute Engine API Switc hto Network Mode
  x-api-slug: google-compute-engine-api
  description: Switches the network mode from auto subnet mode to custom subnet mode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/networks/{network}/switchToCustomMode
  tags: Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalnetworksnetworkswitchtocustommode-post-openapi.md
- name: Google Compute Engine API Get Operations
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of Operation resources contained within the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/operations
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaloperations-get-openapi.md
- name: Google Compute Engine API Delete Operation
  x-api-slug: google-compute-engine-api
  description: Deletes the specified Operations resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/operations/{operation}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaloperationsoperation-delete-openapi.md
- name: Google Compute Engine API Get Operation
  x-api-slug: google-compute-engine-api
  description: Retrieves the specified Operations resource. Get a list of operations
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/operations/{operation}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaloperationsoperation-get-openapi.md
- name: Google Compute Engine API Get Routes
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of Route resources available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/routes
  tags: Route
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalroutes-get-openapi.md
- name: Google Compute Engine API Create Route
  x-api-slug: google-compute-engine-api
  description: Creates a Route resource in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/routes
  tags: Route
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalroutes-post-openapi.md
- name: Google Compute Engine API Delete Route
  x-api-slug: google-compute-engine-api
  description: Deletes the specified Route resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/routes/{route}
  tags: Route
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalroutesroute-delete-openapi.md
- name: Google Compute Engine API Get Route
  x-api-slug: google-compute-engine-api
  description: Returns the specified Route resource. Get a list of available routes
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/routes/{route}
  tags: Route
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalroutesroute-get-openapi.md
- name: Google Compute Engine API Get Snapshots
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of Snapshot resources contained within the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/snapshots
  tags: Snapshot
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalsnapshots-get-openapi.md
- name: Google Compute Engine API Delete Snapshot
  x-api-slug: google-compute-engine-api
  description: |-
    Deletes the specified Snapshot resource. Keep in mind that deleting a single snapshot might not necessarily delete all the data on that snapshot. If any data on the snapshot that is marked for deletion is needed for subsequent snapshots, the data will be moved to the next corresponding snapshot.

    For more information, see Deleting snaphots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/snapshots/{snapshot}
  tags: Snapshot
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalsnapshotssnapshot-delete-openapi.md
- name: Google Compute Engine API Get Snapshot
  x-api-slug: google-compute-engine-api
  description: Returns the specified Snapshot resource. Get a list of available snapshots
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/snapshots/{snapshot}
  tags: Snapshot
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalsnapshotssnapshot-get-openapi.md
- name: Google Compute Engine API Get SSL Certificates
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of SslCertificate resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/sslCertificates
  tags: Certificate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalsslcertificates-get-openapi.md
- name: Google Compute Engine API Create SSL Certificate
  x-api-slug: google-compute-engine-api
  description: Creates a SslCertificate resource in the specified project using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/sslCertificates
  tags: Certificate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalsslcertificates-post-openapi.md
- name: Google Compute Engine API Delete SSL Certificate
  x-api-slug: google-compute-engine-api
  description: Deletes the specified SslCertificate resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/sslCertificates/{sslCertificate}
  tags: Certificate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalsslcertificatessslcertificate-delete-openapi.md
- name: Google Compute Engine API Get SSL Certificate
  x-api-slug: google-compute-engine-api
  description: Returns the specified SslCertificate resource. Get a list of available
    SSL certificates by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/sslCertificates/{sslCertificate}
  tags: Certificate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalsslcertificatessslcertificate-get-openapi.md
- name: Google Compute Engine API Get Target HTTP Proxies
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of TargetHttpProxy resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpProxies
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpproxies-get-openapi.md
- name: Google Compute Engine API Create Target HTTP Proxy
  x-api-slug: google-compute-engine-api
  description: Creates a TargetHttpProxy resource in the specified project using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpProxies
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpproxies-post-openapi.md
- name: Google Compute Engine API Delete Target HTTP Proxy
  x-api-slug: google-compute-engine-api
  description: Deletes the specified TargetHttpProxy resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpProxies/{targetHttpProxy}
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpproxiestargethttpproxy-delete-openapi.md
- name: Google Compute Engine API Get Target HTTP Proxy
  x-api-slug: google-compute-engine-api
  description: Returns the specified TargetHttpProxy resource. Get a list of available
    target HTTP proxies by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpProxies/{targetHttpProxy}
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpproxiestargethttpproxy-get-openapi.md
- name: Google Compute Engine API Get Target HTTPS Proxies
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of TargetHttpsProxy resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpsProxies
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpsproxies-get-openapi.md
- name: Google Compute Engine API Create Target HTTPS Proxy
  x-api-slug: google-compute-engine-api
  description: Creates a TargetHttpsProxy resource in the specified project using
    the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpsProxies
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpsproxies-post-openapi.md
- name: Google Compute Engine API Delete Target HTTPS Proxy
  x-api-slug: google-compute-engine-api
  description: Deletes the specified TargetHttpsProxy resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpsProxies/{targetHttpsProxy}
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpsproxiestargethttpsproxy-delete-openapi.md
- name: Google Compute Engine API Get Target HTTPS Proxy
  x-api-slug: google-compute-engine-api
  description: Returns the specified TargetHttpsProxy resource. Get a list of available
    target HTTPS proxies by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetHttpsProxies/{targetHttpsProxy}
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargethttpsproxiestargethttpsproxy-get-openapi.md
- name: Google Compute Engine API Get Target SSL Proxies
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of TargetSslProxy resources available to the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetSslProxies
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargetsslproxies-get-openapi.md
- name: Google Compute Engine API Create Target SSL Proxy
  x-api-slug: google-compute-engine-api
  description: Creates a TargetSslProxy resource in the specified project using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetSslProxies
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargetsslproxies-post-openapi.md
- name: Google Compute Engine API Delete Target SSL Proxy
  x-api-slug: google-compute-engine-api
  description: Deletes the specified TargetSslProxy resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetSslProxies/{targetSslProxy}
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargetsslproxiestargetsslproxy-delete-openapi.md
- name: Google Compute Engine API Get Target SSL Proxy
  x-api-slug: google-compute-engine-api
  description: Returns the specified TargetSslProxy resource. Get a list of available
    target SSL proxies by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetSslProxies/{targetSslProxy}
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargetsslproxiestargetsslproxy-get-openapi.md
- name: Google Compute Engine API Set Backend Service
  x-api-slug: google-compute-engine-api
  description: Changes the BackendService for TargetSslProxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetSslProxies/{targetSslProxy}/setBackendService
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargetsslproxiestargetsslproxysetbackendservice-post-openapi.md
- name: Google Compute Engine API Set Proxy header Type
  x-api-slug: google-compute-engine-api
  description: Changes the ProxyHeaderType for TargetSslProxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetSslProxies/{targetSslProxy}/setProxyHeader
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargetsslproxiestargetsslproxysetproxyheader-post-openapi.md
- name: Google Compute Engine API Change SSL Certificate
  x-api-slug: google-compute-engine-api
  description: Changes SslCertificates for TargetSslProxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/targetSslProxies/{targetSslProxy}/setSslCertificates
  tags: Certificate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobaltargetsslproxiestargetsslproxysetsslcertificates-post-openapi.md
- name: Google Compute Engine API Get URL Maps
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of UrlMap resources available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps
  tags: URL Map
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmaps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmaps-get-openapi.md
- name: Google Compute Engine API Create URL Map
  x-api-slug: google-compute-engine-api
  description: Creates a UrlMap resource in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps
  tags: URL Map
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmaps-post-openapi.md
- name: Google Compute Engine API Delete URL Map
  x-api-slug: google-compute-engine-api
  description: Deletes the specified UrlMap resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps/{urlMap}
  tags: URL Map
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmap-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmap-delete-openapi.md
- name: Google Compute Engine API Get URL Map
  x-api-slug: google-compute-engine-api
  description: Returns the specified UrlMap resource. Get a list of available URL
    maps by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps/{urlMap}
  tags: URL Map
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmap-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmap-get-openapi.md
- name: Google Compute Engine API Update URL Map
  x-api-slug: google-compute-engine-api
  description: Updates the specified UrlMap resource with the data included in the
    request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps/{urlMap}
  tags: URL Map
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmap-patch-openapi.md
- name: Google Compute Engine API Update URL Map
  x-api-slug: google-compute-engine-api
  description: Updates the specified UrlMap resource with the data included in the
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps/{urlMap}
  tags: URL Map
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmap-put-openapi.md
- name: Google Compute Engine API Invalidate Cache
  x-api-slug: google-compute-engine-api
  description: Initiates a cache invalidation operation, invalidating the specified
    path, scoped to the specified UrlMap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps/{urlMap}/invalidateCache
  tags: Cache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmapinvalidatecache-post-openapi.md
- name: Google Compute Engine API Run Static Validation
  x-api-slug: google-compute-engine-api
  description: Runs static validation for the UrlMap. In particular, the tests of
    the provided UrlMap will be run. Calling this method does NOT create the UrlMap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/global/urlMaps/{urlMap}/validate
  tags: Validation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectglobalurlmapsurlmapvalidate-post-openapi.md
- name: Google Compute Engine API Move Disk
  x-api-slug: google-compute-engine-api
  description: Moves a persistent disk from one zone to another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/moveDisk
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectmovedisk-post-openapi.md
- name: Google Compute Engine API Move Instance
  x-api-slug: google-compute-engine-api
  description: Moves an instance and its attached persistent disks from one zone to
    another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/moveInstance
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectmoveinstance-post-openapi.md
- name: Google Compute Engine API Get Regions
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of region resources available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions
  tags: Region
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregions-get-openapi.md
- name: Google Compute Engine API Get Region
  x-api-slug: google-compute-engine-api
  description: Returns the specified Region resource. Get a list of available regions
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}
  tags: Region
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregion-get-openapi.md
- name: Google Compute Engine API Get Region Addresses
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of addresses contained within the specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionaddresses-get-openapi.md
- name: Google Compute Engine API Create Region Address
  x-api-slug: google-compute-engine-api
  description: Creates an address resource in the specified project using the data
    included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionaddresses-post-openapi.md
- name: Google Compute Engine API Delete Region Address
  x-api-slug: google-compute-engine-api
  description: Deletes the specified address resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses/{address}
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionaddressesaddress-delete-openapi.md
- name: Google Compute Engine API Get Region Address
  x-api-slug: google-compute-engine-api
  description: Returns the specified address resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/addresses/{address}
  tags: Region Address
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionaddressesaddress-get-openapi.md
- name: Google Compute Engine API Get Autoscalers
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of autoscalers contained within the specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionautoscalers-get-openapi.md
- name: Google Compute Engine API Update Autoscaler
  x-api-slug: google-compute-engine-api
  description: Updates an autoscaler in the specified project using the data included
    in the request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionautoscalers-patch-openapi.md
- name: Google Compute Engine API Create Autoscaler
  x-api-slug: google-compute-engine-api
  description: Creates an autoscaler in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionautoscalers-post-openapi.md
- name: Google Compute Engine API Update Autoscaler
  x-api-slug: google-compute-engine-api
  description: Updates an autoscaler in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionautoscalers-put-openapi.md
- name: Google Compute Engine API Delete Autoscaler
  x-api-slug: google-compute-engine-api
  description: Deletes the specified autoscaler.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/autoscalers/{autoscaler}
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionautoscalersautoscaler-delete-openapi.md
- name: Google Compute Engine API Get Autoscaler
  x-api-slug: google-compute-engine-api
  description: Returns the specified autoscaler.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/autoscalers/{autoscaler}
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionautoscalersautoscaler-get-openapi.md
- name: Google Compute Engine API Get Backend Services
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of regional BackendService resources available to
    the specified project in the given region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/backendServices
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionbackendservices-get-openapi.md
- name: Google Compute Engine API Create Backend Service
  x-api-slug: google-compute-engine-api
  description: Creates a regional BackendService resource in the specified project
    using the data included in the request. There are several restrictions and guidelines
    to keep in mind when creating a regional backend service. Read  Restrictions and
    Guidelines for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/backendServices
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionbackendservices-post-openapi.md
- name: Google Compute Engine API Delete Backend Service
  x-api-slug: google-compute-engine-api
  description: Deletes the specified regional BackendService resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionbackendservicesbackendservice-delete-openapi.md
- name: Google Compute Engine API Get Backend Service
  x-api-slug: google-compute-engine-api
  description: Returns the specified regional BackendService resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionbackendservicesbackendservice-get-openapi.md
- name: Google Compute Engine API Update Backend Service
  x-api-slug: google-compute-engine-api
  description: Updates the specified regional BackendService resource with the data
    included in the request. There are several restrictions and guidelines to keep
    in mind when updating a backend service. Read  Restrictions and Guidelines for
    more information. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionbackendservicesbackendservice-patch-openapi.md
- name: Google Compute Engine API Update Backend Service
  x-api-slug: google-compute-engine-api
  description: Updates the specified regional BackendService resource with the data
    included in the request. There are several restrictions and guidelines to keep
    in mind when updating a backend service. Read  Restrictions and Guidelines for
    more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/backendServices/{backendService}
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionbackendservicesbackendservice-put-openapi.md
- name: Google Compute Engine API Get Backend Service Health Check
  x-api-slug: google-compute-engine-api
  description: Gets the most recent health check results for this regional BackendService.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/backendServices/{backendService}/getHealth
  tags: Backend Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionbackendservicesbackendservicegethealth-post-openapi.md
- name: Google Compute Engine API Get Forwarding Rules
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of ForwardingRule resources available to the specified
    project and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/forwardingRules
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionforwardingrules-get-openapi.md
- name: Google Compute Engine API Create Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Creates a ForwardingRule resource in the specified project and region
    using the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/forwardingRules
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionforwardingrules-post-openapi.md
- name: Google Compute Engine API Delete Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Deletes the specified ForwardingRule resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/forwardingRules/{forwardingRule}
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionforwardingrulesforwardingrule-delete-openapi.md
- name: Google Compute Engine API Get Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Returns the specified ForwardingRule resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/forwardingRules/{forwardingRule}
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionforwardingrulesforwardingrule-get-openapi.md
- name: Google Compute Engine API Update Forwarding Rule
  x-api-slug: google-compute-engine-api
  description: Changes target URL for forwarding rule. The new target should be of
    the same type as the old target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/forwardingRules/{forwardingRule}/setTarget
  tags: Forward Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionforwardingrulesforwardingrulesettarget-post-openapi.md
- name: Google Compute Engine API Get Instance Group Managers
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of managed instance groups that are contained within
    the specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagers-get-openapi.md
- name: Google Compute Engine API Create Instance Group Manager
  x-api-slug: google-compute-engine-api
  description: Creates a managed instance group using the information that you specify
    in the request. After the group is created, it schedules an action to create instances
    in the group using the specified instance template. This operation is marked as
    DONE when the group is created even if the instances in the group have not yet
    been created. You must separately verify the status of the individual instances
    with the listmanagedinstances method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagers-post-openapi.md
- name: Google Compute Engine API Delete Instance Group Manager
  x-api-slug: google-compute-engine-api
  description: Deletes the specified managed instance group and all of the instances
    in that group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanager-delete-openapi.md
- name: Google Compute Engine API Get Instance Group Manager
  x-api-slug: google-compute-engine-api
  description: Returns all of the details about the specified managed instance group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanager-get-openapi.md
- name: Google Compute Engine API Schedule Remove instance
  x-api-slug: google-compute-engine-api
  description: Schedules a group action to remove the specified instances from the
    managed instance group. Abandoning an instance does not delete the instance, but
    it does remove the instance from any target pools that are applied by the managed
    instance group. This method reduces the targetSize of the managed instance group
    by the number of instances that you abandon. This operation is marked as DONE
    when the action is scheduled even if the instances have not yet been removed from
    the group. You must separately verify the status of the abandoning action with
    the listmanagedinstances method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}/abandonInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanagerabandoninstances-post-openapi.md
- name: Google Compute Engine API Schedule Delete instance
  x-api-slug: google-compute-engine-api
  description: Schedules a group action to delete the specified instances in the managed
    instance group. The instances are also removed from any target pools of which
    they were a member. This method reduces the targetSize of the managed instance
    group by the number of instances that you delete. This operation is marked as
    DONE when the action is scheduled even if the instances are still being deleted.
    You must separately verify the status of the deleting action with the listmanagedinstances
    method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}/deleteInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanagerdeleteinstances-post-openapi.md
- name: Google Compute Engine API Get instances
  x-api-slug: google-compute-engine-api
  description: Lists the instances in the managed instance group and instances that
    are scheduled to be created. The list includes any current actions that the group
    has scheduled for its instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}/listManagedInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanagerlistmanagedinstances-post-openapi.md
- name: Google Compute Engine API Recreate Instance
  x-api-slug: google-compute-engine-api
  description: Schedules a group action to recreate the specified instances in the
    managed instance group. The instances are deleted and recreated using the current
    instance template for the managed instance group. This operation is marked as
    DONE when the action is scheduled even if the instances have not yet been recreated.
    You must separately verify the status of the recreating action with the listmanagedinstances
    method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}/recreateInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanagerrecreateinstances-post-openapi.md
- name: Google Compute Engine API Resize Instance
  x-api-slug: google-compute-engine-api
  description: Changes the intended size for the managed instance group. If you increase
    the size, the group schedules actions to create new instances using the current
    instance template. If you decrease the size, the group schedules delete actions
    on one or more instances. The resize operation is marked DONE when the resize
    actions are scheduled even if the group has not yet added or deleted any instances.
    You must separately verify the status of the creating or deleting actions with
    the listmanagedinstances method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}/resize
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanagerresize-post-openapi.md
- name: Google Compute Engine API Set Instance Template
  x-api-slug: google-compute-engine-api
  description: Sets the instance template to use when creating new instances or recreating
    instances in this group. Existing instances are not affected.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}/setInstanceTemplate
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanagersetinstancetemplate-post-openapi.md
- name: Google Compute Engine API Set Instance Target Pools
  x-api-slug: google-compute-engine-api
  description: Modifies the target pools to which all new instances in this group
    are assigned. Existing instances in the group are not affected.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroupManagers/{instanceGroupManager}/setTargetPools
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupmanagersinstancegroupmanagersettargetpools-post-openapi.md
- name: Google Compute Engine API Get Instance Groups
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of instance group resources contained within the
    specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroups
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroups-get-openapi.md
- name: Google Compute Engine API Get Instance Group
  x-api-slug: google-compute-engine-api
  description: Returns the specified instance group resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroups/{instanceGroup}
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupsinstancegroup-get-openapi.md
- name: Google Compute Engine API List Instances
  x-api-slug: google-compute-engine-api
  description: Lists the instances in the specified instance group and displays information
    about the named ports. Depending on the specified options, this method can list
    all instances or only the instances that are running.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroups/{instanceGroup}/listInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupsinstancegrouplistinstances-post-openapi.md
- name: Google Compute Engine API Set Named Portal
  x-api-slug: google-compute-engine-api
  description: Sets the named ports for the specified regional instance group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/instanceGroups/{instanceGroup}/setNamedPorts
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregioninstancegroupsinstancegroupsetnamedports-post-openapi.md
- name: Google Compute Engine API Get Operations
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of Operation resources contained within the specified
    region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/operations
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionoperations-get-openapi.md
- name: Google Compute Engine API Delete Operation
  x-api-slug: google-compute-engine-api
  description: Deletes the specified region-specific Operations resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/operations/{operation}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionoperationsoperation-delete-openapi.md
- name: Google Compute Engine API Get Operation
  x-api-slug: google-compute-engine-api
  description: Retrieves the specified region-specific Operations resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/operations/{operation}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionoperationsoperation-get-openapi.md
- name: Google Compute Engine API Get Routers
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of Router resources available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionrouters-get-openapi.md
- name: Google Compute Engine API Create Router
  x-api-slug: google-compute-engine-api
  description: Creates a Router resource in the specified project and region using
    the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionrouters-post-openapi.md
- name: Google Compute Engine API Delete Router
  x-api-slug: google-compute-engine-api
  description: Deletes the specified Router resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers/{router}
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionroutersrouter-delete-openapi.md
- name: Google Compute Engine API Get Router
  x-api-slug: google-compute-engine-api
  description: Returns the specified Router resource. Get a list of available routers
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers/{router}
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionroutersrouter-get-openapi.md
- name: Google Compute Engine API Update Router
  x-api-slug: google-compute-engine-api
  description: Updates the specified Router resource with the data included in the
    request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers/{router}
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionroutersrouter-patch-openapi.md
- name: Google Compute Engine API Update Router
  x-api-slug: google-compute-engine-api
  description: Updates the specified Router resource with the data included in the
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers/{router}
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionroutersrouter-put-openapi.md
- name: Google Compute Engine API Update Router Status
  x-api-slug: google-compute-engine-api
  description: Retrieves runtime information of the specified router.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers/{router}/getRouterStatus
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionroutersroutergetrouterstatus-get-openapi.md
- name: Google Compute Engine API Preview Router
  x-api-slug: google-compute-engine-api
  description: Preview fields auto-generated during router create and update operations.
    Calling this method does NOT create or update the router.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/routers/{router}/preview
  tags: Router
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionroutersrouterpreview-post-openapi.md
- name: Google Compute Engine API Get Subnetworks
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of subnetworks available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/subnetworks
  tags: Subnetwork
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionsubnetworks-get-openapi.md
- name: Google Compute Engine API Create Subnetwork
  x-api-slug: google-compute-engine-api
  description: Creates a subnetwork in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/subnetworks
  tags: Subnetwork
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionsubnetworks-post-openapi.md
- name: Google Compute Engine API Delete Subnetwork
  x-api-slug: google-compute-engine-api
  description: Deletes the specified subnetwork.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/subnetworks/{subnetwork}
  tags: Subnetwork
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionsubnetworkssubnetwork-delete-openapi.md
- name: Google Compute Engine API Get Subnetwork
  x-api-slug: google-compute-engine-api
  description: Returns the specified subnetwork. Get a list of available subnetworks
    list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/subnetworks/{subnetwork}
  tags: Subnetwork
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionsubnetworkssubnetwork-get-openapi.md
- name: Google Compute Engine API Update Subnetwork
  x-api-slug: google-compute-engine-api
  description: Expands the IP CIDR range of the subnetwork to a specified value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/subnetworks/{subnetwork}/expandIpCidrRange
  tags: Subnetwork
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionsubnetworkssubnetworkexpandipcidrrange-post-openapi.md
- name: Google Compute Engine API Get Target Pools
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of target pools available to the specified project
    and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpools-get-openapi.md
- name: Google Compute Engine API Create Target Pool
  x-api-slug: google-compute-engine-api
  description: Creates a target pool in the specified project and region using the
    data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpools-post-openapi.md
- name: Google Compute Engine API Delete Target Pool
  x-api-slug: google-compute-engine-api
  description: Deletes the specified target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-delete-openapi.md
- name: Google Compute Engine API Get Target Pool
  x-api-slug: google-compute-engine-api
  description: Returns the specified target pool. Get a list of available target pools
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpool-get-openapi.md
- name: Google Compute Engine API Add Target Pool Health Check
  x-api-slug: google-compute-engine-api
  description: Adds health check URLs to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}/addHealthCheck
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdhealthcheck-post-openapi.md
- name: Google Compute Engine API Add Instance to Target pool
  x-api-slug: google-compute-engine-api
  description: Adds an instance to a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}/addInstance
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpooladdinstance-post-openapi.md
- name: Google Compute Engine API Get Target Pool Health Check
  x-api-slug: google-compute-engine-api
  description: Gets the most recent health check results for each IP for the instance
    that is referenced by the given target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}/getHealth
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolgethealth-post-openapi.md
- name: Google Compute Engine API Remove Target Pool  Health Check
  x-api-slug: google-compute-engine-api
  description: Removes health check URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}/removeHealthCheck
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremovehealthcheck-post-openapi.md
- name: Google Compute Engine API Remove Instance From Target Pool
  x-api-slug: google-compute-engine-api
  description: Removes instance URL from a target pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}/removeInstance
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolremoveinstance-post-openapi.md
- name: Google Compute Engine API Change Target Pool Backup
  x-api-slug: google-compute-engine-api
  description: Changes a backup target pool's configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetPools/{targetPool}/setBackup
  tags: Target Pool
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetpoolstargetpoolsetbackup-post-openapi.md
- name: Google Compute Engine API Get Target Pool VPN Gateways
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of target VPN gateways available to the specified
    project and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetVpnGateways
  tags: VPN Gateway
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetvpngateways-get-openapi.md
- name: Google Compute Engine API Create Target Pool VPN Gateway
  x-api-slug: google-compute-engine-api
  description: Creates a target VPN gateway in the specified project and region using
    the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetVpnGateways
  tags: VPN Gateway
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetvpngateways-post-openapi.md
- name: Google Compute Engine API Delete Target Pool VPN Gateway
  x-api-slug: google-compute-engine-api
  description: Deletes the specified target VPN gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetVpnGateways/{targetVpnGateway}
  tags: VPN Gateway
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetvpngatewaystargetvpngateway-delete-openapi.md
- name: Google Compute Engine API Get Target Pool VPN Gateway
  x-api-slug: google-compute-engine-api
  description: Returns the specified target VPN gateway. Get a list of available target
    VPN gateways by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/targetVpnGateways/{targetVpnGateway}
  tags: VPN Gateway
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregiontargetvpngatewaystargetvpngateway-get-openapi.md
- name: Google Compute Engine API Get VPN Tunnels
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of VpnTunnel resources contained in the specified
    project and region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/vpnTunnels
  tags: VPN Tunnel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionvpntunnels-get-openapi.md
- name: Google Compute Engine API Create VPN Tunnel
  x-api-slug: google-compute-engine-api
  description: Creates a VpnTunnel resource in the specified project and region using
    the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/vpnTunnels
  tags: VPN Tunnel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionvpntunnels-post-openapi.md
- name: Google Compute Engine API Delete VPN Tunnel
  x-api-slug: google-compute-engine-api
  description: Deletes the specified VpnTunnel resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/vpnTunnels/{vpnTunnel}
  tags: VPN Tunnel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionvpntunnelsvpntunnel-delete-openapi.md
- name: Google Compute Engine API Get VPN Tunnel
  x-api-slug: google-compute-engine-api
  description: Returns the specified VpnTunnel resource. Get a list of available VPN
    tunnels by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/regions/{region}/vpnTunnels/{vpnTunnel}
  tags: VPN Tunnel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectregionsregionvpntunnelsvpntunnel-get-openapi.md
- name: Google Compute Engine API Set Common Instance Metadata
  x-api-slug: google-compute-engine-api
  description: Sets metadata common to all instances within the specified project
    using the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/setCommonInstanceMetadata
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectsetcommoninstancemetadata-post-openapi.md
- name: Google Compute Engine API Set Usage Export Bucket
  x-api-slug: google-compute-engine-api
  description: Enables the usage export feature and sets the usage export bucket where
    reports are stored. If you provide an empty request body using this method, the
    usage export feature will be disabled.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/setUsageExportBucket
  tags: Bucket
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectsetusageexportbucket-post-openapi.md
- name: Google Compute Engine API Target HTTP Proxies URL Map
  x-api-slug: google-compute-engine-api
  description: Changes the URL map for TargetHttpProxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/targetHttpProxies/{targetHttpProxy}/setUrlMap
  tags: URL Map
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projecttargethttpproxiestargethttpproxyseturlmap-post-openapi.md
- name: Google Compute Engine API Replace SSL Certificate for Target HTTP PRoxy
  x-api-slug: google-compute-engine-api
  description: Replaces SslCertificates for TargetHttpsProxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/targetHttpsProxies/{targetHttpsProxy}/setSslCertificates
  tags: Certificate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projecttargethttpsproxiestargethttpsproxysetsslcertificates-post-openapi.md
- name: Google Compute Engine API Change URL Map for Target HTTP PRoxy
  x-api-slug: google-compute-engine-api
  description: Changes the URL map for TargetHttpsProxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/targetHttpsProxies/{targetHttpsProxy}/setUrlMap
  tags: Proxy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projecttargethttpsproxiestargethttpsproxyseturlmap-post-openapi.md
- name: Google Compute Engine API Get Zones
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of Zone resources available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones
  tags: Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzones-get-openapi.md
- name: Google Compute Engine API Get Zone
  x-api-slug: google-compute-engine-api
  description: Returns the specified Zone resource. Get a list of available zones
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}
  tags: Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszone-get-openapi.md
- name: Google Compute Engine API Get Zone Autoscalers
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of autoscalers contained within the specified zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneautoscalers-get-openapi.md
- name: Google Compute Engine API Update Zone Autoscaler
  x-api-slug: google-compute-engine-api
  description: Updates an autoscaler in the specified project using the data included
    in the request. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneautoscalers-patch-openapi.md
- name: Google Compute Engine API Create Zone Autoscaler
  x-api-slug: google-compute-engine-api
  description: Creates an autoscaler in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneautoscalers-post-openapi.md
- name: Google Compute Engine API Update Zone Autoscaler
  x-api-slug: google-compute-engine-api
  description: Updates an autoscaler in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/autoscalers
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneautoscalers-put-openapi.md
- name: Google Compute Engine API Delete Zone Autoscaler
  x-api-slug: google-compute-engine-api
  description: Deletes the specified autoscaler.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/autoscalers/{autoscaler}
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneautoscalersautoscaler-delete-openapi.md
- name: Google Compute Engine API UpGetdate Zone Autoscaler
  x-api-slug: google-compute-engine-api
  description: Returns the specified autoscaler resource. Get a list of available
    autoscalers by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/autoscalers/{autoscaler}
  tags: Autoscaler
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneautoscalersautoscaler-get-openapi.md
- name: Google Compute Engine API Get Zone Disk Types
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of disk types available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/diskTypes
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisktypes-get-openapi.md
- name: Google Compute Engine API Get Zone Disk Type
  x-api-slug: google-compute-engine-api
  description: Returns the specified disk type. Get a list of available disk types
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/diskTypes/{diskType}
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisktypesdisktype-get-openapi.md
- name: Google Compute Engine API Get Zone Disks
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of persistent disks contained within the specified
    zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisks-get-openapi.md
- name: Google Compute Engine API Create Zone Disk
  x-api-slug: google-compute-engine-api
  description: Creates a persistent disk in the specified project using the data in
    the request. You can create a disk with a sourceImage, a sourceSnapshot, or create
    an empty 500 GB data disk by omitting all properties. You can also create a disk
    that is larger than the default size by specifying the sizeGb property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisks-post-openapi.md
- name: Google Compute Engine API Delete Zone Disk
  x-api-slug: google-compute-engine-api
  description: Deletes the specified persistent disk. Deleting a disk removes its
    data permanently and is irreversible. However, deleting a disk does not delete
    any snapshots previously made from the disk. You must separately delete snapshots.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisksdisk-delete-openapi.md
- name: Google Compute Engine API Get Zone Disk
  x-api-slug: google-compute-engine-api
  description: Returns a specified persistent disk. Get a list of available persistent
    disks by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisksdisk-get-openapi.md
- name: Google Compute Engine API Create Snapshot of Zone Disk
  x-api-slug: google-compute-engine-api
  description: Creates a snapshot of a specified persistent disk.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}/createSnapshot
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisksdiskcreatesnapshot-post-openapi.md
- name: Google Compute Engine API Resize Zone Disk
  x-api-slug: google-compute-engine-api
  description: Resizes the specified persistent disk.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/disks/{disk}/resize
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonedisksdiskresize-post-openapi.md
- name: Google Compute Engine API Get Zone Instance Group Managers
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of managed instance groups that are contained within
    the specified project and zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers
  tags: Group Manager
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagers-get-openapi.md
- name: Google Compute Engine API Create Zone Instance Group Manager
  x-api-slug: google-compute-engine-api
  description: Creates a managed instance group using the information that you specify
    in the request. After the group is created, it schedules an action to create instances
    in the group using the specified instance template. This operation is marked as
    DONE when the group is created even if the instances in the group have not yet
    been created. You must separately verify the status of the individual instances
    with the listmanagedinstances method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers
  tags: Group Manager
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagers-post-openapi.md
- name: Google Compute Engine API Delete Zone Instance Group Manager
  x-api-slug: google-compute-engine-api
  description: Deletes the specified managed instance group and all of the instances
    in that group. Note that the instance group must not belong to a backend service.
    Read  Deleting an instance group for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}
  tags: Group Manager
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanager-delete-openapi.md
- name: Google Compute Engine API Get Zone Instance Group Manager
  x-api-slug: google-compute-engine-api
  description: Returns all of the details about the specified managed instance group.
    Get a list of available managed instance groups by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}
  tags: Group Manager
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanager-get-openapi.md
- name: Google Compute Engine API Schedule Action to Abandon Instance
  x-api-slug: google-compute-engine-api
  description: Schedules a group action to remove the specified instances from the
    managed instance group. Abandoning an instance does not delete the instance, but
    it does remove the instance from any target pools that are applied by the managed
    instance group. This method reduces the targetSize of the managed instance group
    by the number of instances that you abandon. This operation is marked as DONE
    when the action is scheduled even if the instances have not yet been removed from
    the group. You must separately verify the status of the abandoning action with
    the listmanagedinstances method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}/abandonInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanagerabandoninstances-post-openapi.md
- name: Google Compute Engine API Schedule Action to Delete Instance
  x-api-slug: google-compute-engine-api
  description: Schedules a group action to delete the specified instances in the managed
    instance group. The instances are also removed from any target pools of which
    they were a member. This method reduces the targetSize of the managed instance
    group by the number of instances that you delete. This operation is marked as
    DONE when the action is scheduled even if the instances are still being deleted.
    You must separately verify the status of the deleting action with the listmanagedinstances
    method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}/deleteInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanagerdeleteinstances-post-openapi.md
- name: Google Compute Engine API Get Zone Managed Instances
  x-api-slug: google-compute-engine-api
  description: Lists all of the instances in the managed instance group. Each instance
    in the list has a currentAction, which indicates the action that the managed instance
    group is performing on the instance. For example, if the group is still creating
    an instance, the currentAction is CREATING. If a previous action failed, the list
    displays the errors for that failed action.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}/listManagedInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanagerlistmanagedinstances-post-openapi.md
- name: Google Compute Engine API Schedule Recreate of Instance
  x-api-slug: google-compute-engine-api
  description: Schedules a group action to recreate the specified instances in the
    managed instance group. The instances are deleted and recreated using the current
    instance template for the managed instance group. This operation is marked as
    DONE when the action is scheduled even if the instances have not yet been recreated.
    You must separately verify the status of the recreating action with the listmanagedinstances
    method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}/recreateInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanagerrecreateinstances-post-openapi.md
- name: Google Compute Engine API Schedule Resize of Instance
  x-api-slug: google-compute-engine-api
  description: Resizes the managed instance group. If you increase the size, the group
    creates new instances using the current instance template. If you decrease the
    size, the group deletes instances. The resize operation is marked DONE when the
    resize actions are scheduled even if the group has not yet added or deleted any
    instances. You must separately verify the status of the creating or deleting actions
    with the listmanagedinstances method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}/resize
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanagerresize-post-openapi.md
- name: Google Compute Engine API Set  Zone Managed Instance Template
  x-api-slug: google-compute-engine-api
  description: Specifies the instance template to use when creating new instances
    in this group. The templates for existing instances in the group do not change
    unless you recreate them.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}/setInstanceTemplate
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanagersetinstancetemplate-post-openapi.md
- name: Google Compute Engine API Modify  Zone Managed Instance Target Pool
  x-api-slug: google-compute-engine-api
  description: Modifies the target pools to which all instances in this managed instance
    group are assigned. The target pools automatically apply to all of the instances
    in the managed instance group. This operation is marked DONE when you make the
    request even if the instances have not yet been added to their target pools. The
    change might take some time to apply to all of the instances in the group depending
    on the size of the group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroupManagers/{instanceGroupManager}/setTargetPools
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupmanagersinstancegroupmanagersettargetpools-post-openapi.md
- name: Google Compute Engine API Get Zone Instance Groups
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of instance groups that are located in the specified
    project and zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroups-get-openapi.md
- name: Google Compute Engine API Create Zone Instance Group
  x-api-slug: google-compute-engine-api
  description: Creates an instance group in the specified project using the parameters
    that are included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroups-post-openapi.md
- name: Google Compute Engine API Delete Zone Instance Group
  x-api-slug: google-compute-engine-api
  description: Deletes the specified instance group. The instances in the group are
    not deleted. Note that instance group must not belong to a backend service. Read  Deleting
    an instance group for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups/{instanceGroup}
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupsinstancegroup-delete-openapi.md
- name: Google Compute Engine API Get Zone Instance Group
  x-api-slug: google-compute-engine-api
  description: Returns the specified instance group. Get a list of available instance
    groups by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups/{instanceGroup}
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupsinstancegroup-get-openapi.md
- name: Google Compute Engine API Add Instance to Zone Instance Group
  x-api-slug: google-compute-engine-api
  description: Adds a list of instances to the specified instance group. All of the
    instances in the instance group must be in the same network/subnetwork. Read  Adding
    instances for more information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups/{instanceGroup}/addInstances
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupsinstancegroupaddinstances-post-openapi.md
- name: Google Compute Engine API Get Instance in Zone Instance Group
  x-api-slug: google-compute-engine-api
  description: Lists the instances in the specified instance group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups/{instanceGroup}/listInstances
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupsinstancegrouplistinstances-post-openapi.md
- name: Google Compute Engine API Remove Instance in Zone Instance Group
  x-api-slug: google-compute-engine-api
  description: Removes one or more instances from the specified instance group, but
    does not delete those instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups/{instanceGroup}/removeInstances
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupsinstancegroupremoveinstances-post-openapi.md
- name: Google Compute Engine API Set Named Ports for Zone Instance Group
  x-api-slug: google-compute-engine-api
  description: Sets the named ports for the specified instance group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instanceGroups/{instanceGroup}/setNamedPorts
  tags: Instance Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancegroupsinstancegroupsetnamedports-post-openapi.md
- name: Google Compute Engine API Get Zone Instances
  x-api-slug: google-compute-engine-api
  description: Retrieves the list of instances contained within the specified zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstances-get-openapi.md
- name: Google Compute Engine API Create Zone Instance
  x-api-slug: google-compute-engine-api
  description: Creates an instance resource in the specified project using the data
    included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstances-post-openapi.md
- name: Google Compute Engine API Delete Zone Instance
  x-api-slug: google-compute-engine-api
  description: Deletes the specified Instance resource. For more information, see
    Stopping or Deleting an Instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstance-delete-openapi.md
- name: Google Compute Engine API Get Zone Instance
  x-api-slug: google-compute-engine-api
  description: Returns the specified Instance resource. Get a list of available instances
    by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstance-get-openapi.md
- name: Google Compute Engine API Add Access to Zone Instance
  x-api-slug: google-compute-engine-api
  description: Adds an access config to an instance's network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/addAccessConfig
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstanceaddaccessconfig-post-openapi.md
- name: Google Compute Engine API Attach Disk to Zone Instance
  x-api-slug: google-compute-engine-api
  description: Attaches a Disk resource to an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/attachDisk
  tags: Disk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstanceattachdisk-post-openapi.md
- name: Google Compute Engine API Delete Access to Zone Instance
  x-api-slug: google-compute-engine-api
  description: Deletes an access config from an instance's network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/deleteAccessConfig
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancedeleteaccessconfig-post-openapi.md
- name: Google Compute Engine API Detach Disk from Zone Instance
  x-api-slug: google-compute-engine-api
  description: Detaches a disk from an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/detachDisk
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancedetachdisk-post-openapi.md
- name: Google Compute Engine API Reset Zone Instance
  x-api-slug: google-compute-engine-api
  description: Performs a hard reset on the instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/reset
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancereset-post-openapi.md
- name: Google Compute Engine API Get Zone Instance Serial Port
  x-api-slug: google-compute-engine-api
  description: Returns the specified instance's serial port output.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/serialPort
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstanceserialport-get-openapi.md
- name: Google Compute Engine API Set Zone Instance Disk Auto Delete
  x-api-slug: google-compute-engine-api
  description: Sets the auto-delete flag for a disk attached to an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/setDiskAutoDelete
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancesetdiskautodelete-post-openapi.md
- name: Google Compute Engine API Set Zone Instance Machine Type
  x-api-slug: google-compute-engine-api
  description: Changes the machine type for a stopped instance to the machine type
    specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/setMachineType
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancesetmachinetype-post-openapi.md
- name: Google Compute Engine API Set Zone Instance Metadata
  x-api-slug: google-compute-engine-api
  description: Sets metadata for the specified instance to the data included in the
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/setMetadata
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancesetmetadata-post-openapi.md
- name: Google Compute Engine API Set Zone Instance Scheduling
  x-api-slug: google-compute-engine-api
  description: Sets an instance's scheduling options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/setScheduling
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancesetscheduling-post-openapi.md
- name: Google Compute Engine API Set Zone Instance Service Account
  x-api-slug: google-compute-engine-api
  description: Sets the service account on the instance. For more information, read
    Changing the service account and access scopes for an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/setServiceAccount
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancesetserviceaccount-post-openapi.md
- name: Google Compute Engine API Set Zone Instance Tags
  x-api-slug: google-compute-engine-api
  description: Sets tags for the specified instance to the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/setTags
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancesettags-post-openapi.md
- name: Google Compute Engine API Start Zone Instance
  x-api-slug: google-compute-engine-api
  description: Starts an instance that was stopped using the using the instances().stop
    method. For more information, see Restart an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/start
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancestart-post-openapi.md
- name: Google Compute Engine API Start Zone Instance with Encryption Key
  x-api-slug: google-compute-engine-api
  description: Starts an instance that was stopped using the using the instances().stop
    method. For more information, see Restart an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/startWithEncryptionKey
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancestartwithencryptionkey-post-openapi.md
- name: Google Compute Engine API Stop Zone Instance
  x-api-slug: google-compute-engine-api
  description: Stops a running instance, shutting it down cleanly, and allows you
    to restart the instance at a later time. Stopped instances do not incur per-minute,
    virtual machine usage charges while they are stopped, but any resources that the
    virtual machine is using, such as persistent disks and static IP addresses, will
    continue to be charged until they are deleted. For more information, see Stopping
    an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/instances/{instance}/stop
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneinstancesinstancestop-post-openapi.md
- name: Google Compute Engine API Get Zone Instance Machine Types
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of machine types available to the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/machineTypes
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonemachinetypes-get-openapi.md
- name: Google Compute Engine API Get Zone Instance Machine Type
  x-api-slug: google-compute-engine-api
  description: Returns the specified machine type. Get a list of available machine
    types by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/machineTypes/{machineType}
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonemachinetypesmachinetype-get-openapi.md
- name: Google Compute Engine API Get Zone Instance Machine Operatons
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of Operation resources contained within the specified
    zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/operations
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneoperations-get-openapi.md
- name: Google Compute Engine API Delete Zone Instance Machine Operaton
  x-api-slug: google-compute-engine-api
  description: Deletes the specified zone-specific Operations resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/operations/{operation}
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneoperationsoperation-delete-openapi.md
- name: Google Compute Engine API Get Zone Instance Machine Operaton
  x-api-slug: google-compute-engine-api
  description: Retrieves the specified zone-specific Operations resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/operations/{operation}
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszoneoperationsoperation-get-openapi.md
- name: Google Compute Engine API Get Zone Target Instances
  x-api-slug: google-compute-engine-api
  description: Retrieves a list of TargetInstance resources available to the specified
    project and zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/targetInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonetargetinstances-get-openapi.md
- name: Google Compute Engine API Create Zone Target Instance
  x-api-slug: google-compute-engine-api
  description: Creates a TargetInstance resource in the specified project and zone
    using the data included in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/targetInstances
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonetargetinstances-post-openapi.md
- name: Google Compute Engine API Delete Zone Target Instance
  x-api-slug: google-compute-engine-api
  description: Deletes the specified TargetInstance resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/targetInstances/{targetInstance}
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonetargetinstancestargetinstance-delete-openapi.md
- name: Google Compute Engine API Get Zone Target Instance
  x-api-slug: google-compute-engine-api
  description: Returns the specified TargetInstance resource. Get a list of available
    target instances by making a list() request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects//{project}/zones/{zone}/targetInstances/{targetInstance}
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/projectzoneszonetargetinstancestargetinstance-get-openapi.md
- name: Google Compute Engine API
  x-api-slug: google-compute-engine-api
  description: Google Compute Engine delivers virtual machines running in Googles
    innovative data centers and worldwide fiber network. Compute Engines tooling and
    workflow support enable scaling from single instances to global, load-balanced
    cloud computing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google_Compute_Engine_logo.png
  humanURL: https://cloud.google.com/compute/
  baseURL: ://www.googleapis.com//compute/v1/projects
  tags: Google Compute Engine
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-compute-engine/master/_listings/google-compute-engine/openapi.md
x-common:
- type: x-code
  url: https://cloud.google.com/compute/docs/api/libraries
- type: x-documentation
  url: https://cloud.google.com/compute/docs/reference/latest/
- type: x-guides
  url: https://cloud.google.com/compute/docs/api/how-tos/how-tos
- type: x-rate-limits
  url: https://cloud.google.com/compute/docs/api-rate-limits
- type: x-sla
  url: https://cloud.google.com/compute/sla
- type: x-website
  url: https://cloud.google.com/compute/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---