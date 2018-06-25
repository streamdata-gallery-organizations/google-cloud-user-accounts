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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud User Accounts API Get Groups
  x-api-slug: google-cloud-user-accounts-api
  description: Retrieves the list of groups contained within the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups
  tags: Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroups-get-openapi.md
- name: Google Cloud User Accounts API Create Group
  x-api-slug: google-cloud-user-accounts-api
  description: Creates a Group resource in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups
  tags: Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroups-post-openapi.md
- name: Google Cloud User Accounts API Delete Group
  x-api-slug: google-cloud-user-accounts-api
  description: Deletes the specified Group resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{groupName}
  tags: Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupname-delete-openapi.md
- name: Google Cloud User Accounts API Get Group
  x-api-slug: google-cloud-user-accounts-api
  description: Returns the specified Group resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{groupName}
  tags: Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupname-get-openapi.md
- name: Google Cloud User Accounts API Add User To Group
  x-api-slug: google-cloud-user-accounts-api
  description: Adds users to the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{groupName}/addMember
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupnameaddmember-post-openapi.md
- name: Google Cloud User Accounts API Remove Use From Group
  x-api-slug: google-cloud-user-accounts-api
  description: Removes users from the specified group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{groupName}/removeMember
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsgroupnameremovemember-post-openapi.md
- name: Google Cloud User Accounts API Get IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{resource}/getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcegetiampolicy-get-openapi.md
- name: Google Cloud User Accounts API Set IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{resource}/setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcesetiampolicy-post-openapi.md
- name: Google Cloud User Accounts API Test IAM Permissions
  x-api-slug: google-cloud-user-accounts-api
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/groups/{resource}/testIamPermissions
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalgroupsresourcetestiampermissions-post-openapi.md
- name: Google Cloud User Accounts API Get Operations
  x-api-slug: google-cloud-user-accounts-api
  description: Retrieves the list of operation resources contained within the specified
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/operations
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobaloperations-get-openapi.md
- name: Google Cloud User Accounts API Delete Operation
  x-api-slug: google-cloud-user-accounts-api
  description: Deletes the specified operation resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/operations/{operation}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobaloperationsoperation-delete-openapi.md
- name: Google Cloud User Accounts API Get Operation
  x-api-slug: google-cloud-user-accounts-api
  description: Retrieves the specified operation resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/operations/{operation}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobaloperationsoperation-get-openapi.md
- name: Google Cloud User Accounts API Get Users
  x-api-slug: google-cloud-user-accounts-api
  description: Retrieves a list of users contained within the specified project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusers-get-openapi.md
- name: Google Cloud User Accounts API Create User
  x-api-slug: google-cloud-user-accounts-api
  description: Creates a User resource in the specified project using the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusers-post-openapi.md
- name: Google Cloud User Accounts API Get User IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{resource}/getIamPolicy
  tags: User IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersresourcegetiampolicy-get-openapi.md
- name: Google Cloud User Accounts API Set User IAM Policy
  x-api-slug: google-cloud-user-accounts-api
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{resource}/setIamPolicy
  tags: User IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersresourcesetiampolicy-post-openapi.md
- name: Google Cloud User Accounts API Test User IAM Permissions
  x-api-slug: google-cloud-user-accounts-api
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{resource}/testIamPermissions
  tags: User IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersresourcetestiampermissions-post-openapi.md
- name: Google Cloud User Accounts API Delete User
  x-api-slug: google-cloud-user-accounts-api
  description: Deletes the specified User resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{user}
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuser-delete-openapi.md
- name: Google Cloud User Accounts API Get User
  x-api-slug: google-cloud-user-accounts-api
  description: Returns the specified User resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{user}
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuser-get-openapi.md
- name: Google Cloud User Accounts API Add Public Key
  x-api-slug: google-cloud-user-accounts-api
  description: Adds a public key to the specified User resource with the data included
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{user}/addPublicKey
  tags: Public Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuseraddpublickey-post-openapi.md
- name: Google Cloud User Accounts API Remove Public Key
  x-api-slug: google-cloud-user-accounts-api
  description: Removes the specified public key from the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/global/users/{user}/removePublicKey
  tags: Public Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectglobalusersuserremovepublickey-post-openapi.md
- name: Google Cloud User Accounts API Get Public Keys
  x-api-slug: google-cloud-user-accounts-api
  description: Returns a list of authorized public keys for a specific user account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/zones/{zone}/authorizedKeysView/{user}
  tags: Public Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectzoneszoneauthorizedkeysviewuser-post-openapi.md
- name: Google Cloud User Accounts API Get Linux Account Views
  x-api-slug: google-cloud-user-accounts-api
  description: Retrieves a list of user accounts for an instance within a specific
    project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects//{project}/zones/{zone}/linuxAccountViews
  tags: Public Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/projectzoneszonelinuxaccountviews-post-openapi.md
- name: Google Cloud User Accounts API
  x-api-slug: google-cloud-user-accounts-api
  description: Service for managing the global Google Cloud user accounts. This API
    reference is organized by resource type. Each resource type has one or more data
    representations and one or more methods.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/compute/docs/access/user-accounts/api/latest/
  baseURL: ://www.googleapis.com//clouduseraccounts/vm_alpha/projects
  tags: Google Cloud User Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-user-accounts/master/_listings/google-cloud-user-accounts/openapi.md
x-common:
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