---
name: Sustainable Facilities Tool API
x-slug: sustainable-facilities-tool-api
description: Our core API allows developers to interact with the Sustainable Facilities
  Tool programmatically. Its designed for public use and to be easily integrated into
  other applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Build
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/apis.md
specificationVersion: "0.14"
apis:
- name: Sustainable Facilities Tool API Returns all building systems.
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all building systems.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems
  tags: Building Systems
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/buildingsystems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/buildingsystems-get-openapi.md
- name: Sustainable Facilities Tool API Returns a building system by parameter.
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a building system by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}
  tags: Building Systems
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameter-get-openapi.md
- name: Sustainable Facilities Tool API Returns Building System Resources
  x-api-slug: sustainable-facilities-tool-api
  description: Returns informational resources for the building system selected by
    parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}/resources
  tags: Building System Resources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterresources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterresources-get-openapi.md
- name: Sustainable Facilities Tool API
  x-api-slug: sustainable-facilities-tool-api
  description: Our core API allows developers to interact with the Sustainable Facilities
    Tool programmatically. Its designed for public use and to be easily integrated
    into other applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1/
  tags: Build
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/sustainable-facilities-tool-api/openapi.md
x-common:
- type: x-developer
  url: https://sftool.gov/developers
- type: x-terms-of-service
  url: https://sftool.gov/developer/terms-of-use
- type: x-twitter
  url: https://twitter.com/sftool
- type: x-website
  url: https://sftool.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---