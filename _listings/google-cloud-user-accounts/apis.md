---
name: Google Cloud User Accounts
x-slug: google-cloud-user-accounts
description: Service for managing the global Google Cloud user accounts. This API
  reference is organized by resource type. Each resource type has one or more data
  representations and one or more methods.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud User Accounts
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/apis.md
specificationVersion: "0.14"
apis:
- name: Cloud User Accounts - Get Groups
  x-api-slug: projectglobalgroups-get
  description: Retrieves the list of groups contained within the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroups-get-openapi.md
- name: Cloud User Accounts - Create Group
  x-api-slug: projectglobalgroups-post
  description: Creates a Group resource in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroups-post-openapi.md
- name: Cloud User Accounts - Delete Group
  x-api-slug: projectglobalgroupsgroupname-delete
  description: Deletes the specified Group resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupname-delete-openapi.md
- name: Cloud User Accounts - Get Group
  x-api-slug: projectglobalgroupsgroupname-get
  description: Returns the specified Group resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupname-get-openapi.md
- name: Cloud User Accounts - Add User To Group
  x-api-slug: projectglobalgroupsgroupnameaddmember-post
  description: Adds users to the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupnameaddmember-post-openapi.md
- name: Cloud User Accounts - Remove Use From Group
  x-api-slug: projectglobalgroupsgroupnameremovemember-post
  description: Removes users from the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupnameremovemember-post-openapi.md
- name: Cloud User Accounts - Get IAM Policy
  x-api-slug: projectglobalgroupsresourcegetiampolicy-get
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcegetiampolicy-get-openapi.md
- name: Cloud User Accounts - Set IAM Policy
  x-api-slug: projectglobalgroupsresourcesetiampolicy-post
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcesetiampolicy-post-openapi.md
- name: Cloud User Accounts - Test IAM Permissions
  x-api-slug: projectglobalgroupsresourcetestiampermissions-post
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcetestiampermissions-post-openapi.md
- name: Cloud User Accounts - Get Operations
  x-api-slug: projectglobaloperations-get
  description: Retrieves the list of operation resources contained within the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobaloperations-get-openapi.md
- name: Cloud User Accounts - Delete Operation
  x-api-slug: projectglobaloperationsoperation-delete
  description: Deletes the specified operation resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobaloperationsoperation-delete-openapi.md
- name: Cloud User Accounts - Get Operation
  x-api-slug: projectglobaloperationsoperation-get
  description: Retrieves the specified operation resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobaloperationsoperation-get-openapi.md
- name: Cloud User Accounts - Get Users
  x-api-slug: projectglobalusers-get
  description: Retrieves a list of users contained within the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusers-get-openapi.md
- name: Cloud User Accounts - Create User
  x-api-slug: projectglobalusers-post
  description: Creates a User resource in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusers-post-openapi.md
- name: Cloud User Accounts - Get User IAM Policy
  x-api-slug: projectglobalusersresourcegetiampolicy-get
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersresourcegetiampolicy-get-openapi.md
- name: Cloud User Accounts - Set User IAM Policy
  x-api-slug: projectglobalusersresourcesetiampolicy-post
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersresourcesetiampolicy-post-openapi.md
- name: Cloud User Accounts - Test User IAM Permissions
  x-api-slug: projectglobalusersresourcetestiampermissions-post
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersresourcetestiampermissions-post-openapi.md
- name: Cloud User Accounts - Delete User
  x-api-slug: projectglobalusersuser-delete
  description: Deletes the specified User resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuser-delete-openapi.md
- name: Cloud User Accounts - Get User
  x-api-slug: projectglobalusersuser-get
  description: Returns the specified User resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuser-get-openapi.md
- name: Cloud User Accounts - Add Public Key
  x-api-slug: projectglobalusersuseraddpublickey-post
  description: Adds a public key to the specified User resource with the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuseraddpublickey-post-openapi.md
- name: Cloud User Accounts - Remove Public Key
  x-api-slug: projectglobalusersuserremovepublickey-post
  description: Removes the specified public key from the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuserremovepublickey-post-openapi.md
- name: Cloud User Accounts - Get Public Keys
  x-api-slug: projectzoneszoneauthorizedkeysviewuser-post
  description: Returns a list of authorized public keys for a specific user account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectzoneszoneauthorizedkeysviewuser-post-openapi.md
- name: Cloud User Accounts - Get Linux Account Views
  x-api-slug: projectzoneszonelinuxaccountviews-post
  description: Retrieves a list of user accounts for an instance within a specific
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Authentication, Management, Users, Google APIs, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectzoneszonelinuxaccountviews-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.storage.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.user.accounts.stack.network
- type: x-code
  url: https://cloud.google.com/compute/docs/access/user-accounts/api/libraries
- type: x-guides
  url: https://cloud.google.com/compute/docs/access/user-accounts/api/how-tos/how-tos
- type: x-website
  url: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---