---
swagger: "2.0"
x-collection-name: eMuseum API docs
x-complete: 1
info:
  title: eMuseum API
  description: developed-in-partnership-with-museums-the-museum-system-makes-capturing-managing-and-accessing-collection-information-quick-and-easy--emuseum-is-a-webbased-software-program-that-integrates-seamlessly-with-tms-and-other-collection-management-systems-to-dynamically-publish-information-to-your-website-intranet-and-kiosks--this-api-delivers-search-information-and-images-from-tms--emuseum-to-gsa-gov-
  version: 1.0.0
host: gsafinearts.pbs.gsa.gov
basePath: /emuseum/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search/buildings:
    get:
      summary: Buildings
      description: Search for art by building
      operationId: searchBuildings
      x-api-path-slug: searchbuildings-get
      responses:
        200:
          description: OK
      tags:
      - Buildings
  /id/buildings/{id}:
    get:
      summary: Building
      description: Get Art By Building
      operationId: getBuilding
      x-api-path-slug: idbuildingsid-get
      responses:
        200:
          description: OK
      tags:
      - Buildings
---