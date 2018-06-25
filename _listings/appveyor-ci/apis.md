---
name: AppVeyor CI
x-slug: appveyor-ci
description: We provide continuous integration tools for Windows developers. The service
  is offered for free to open-source projects, we offer subscriptions for private
  projects and AppVeyor Enterprise installations on customer premises.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
x-kinRank: "7"
x-alexaRank: "35479"
tags: Build
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/apis.md
specificationVersion: "0.14"
apis:
- name: App Veyor Get Buildjobs Jobid Artifacts
  x-api-slug: app-veyor
  description: Get buildjobs jobid artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts
  tags: Builds,Jobs,,Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifacts-get-openapi.md
- name: App Veyor Parameters Buildjobs Jobid Artifacts
  x-api-slug: app-veyor
  description: Parameters buildjobs jobid artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts
  tags: Builds,Jobs,,Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifacts-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifacts-parameters-openapi.md
- name: App Veyor Get Buildjobs Jobid Artifacts Artifactfilename
  x-api-slug: app-veyor
  description: Get buildjobs jobid artifacts artifactfilename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts/{artifactFileName}
  tags: Builds,Jobs,,Artifacts,Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-get-openapi.md
- name: App Veyor Parameters Buildjobs Jobid Artifacts Artifactfilename
  x-api-slug: app-veyor
  description: Parameters buildjobs jobid artifacts artifactfilename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts/{artifactFileName}
  tags: Builds,Jobs,,Artifacts,Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-parameters-openapi.md
- name: App Veyor Get Buildjobs Jobid Log
  x-api-slug: app-veyor
  description: Get buildjobs jobid log.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/log
  tags: Builds,Jobs,,Log
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidlog-get-openapi.md
- name: App Veyor Parameters Buildjobs Jobid Log
  x-api-slug: app-veyor
  description: Parameters buildjobs jobid log.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/log
  tags: Builds,Jobs,,Log
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidlog-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildjobsjobidlog-parameters-openapi.md
- name: App Veyor Post Builds
  x-api-slug: app-veyor
  description: Post builds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//builds
  tags: Builds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/builds-post-openapi.md
- name: App Veyor Delete Builds Accountname Projectslug Buildversion
  x-api-slug: app-veyor
  description: Delete builds accountname projectslug buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//builds/{accountName}/{projectSlug}/{buildVersion}
  tags: Builds,AccountName,ProjectSlug,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildsaccountnameprojectslugbuildversion-delete-openapi.md
- name: App Veyor Parameters Builds Accountname Projectslug Buildversion
  x-api-slug: app-veyor
  description: Parameters builds accountname projectslug buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//builds/{accountName}/{projectSlug}/{buildVersion}
  tags: Builds,AccountName,ProjectSlug,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/buildsaccountnameprojectslugbuildversion-parameters-openapi.md
- name: App Veyor Get Projects Status Statusbadgeid Branch Buildbranch
  x-api-slug: app-veyor
  description: Get projects status statusbadgeid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{statusBadgeId}/branch/{buildBranch}
  tags: Projects,Status,StatusBadgeId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsstatusstatusbadgeidbranchbuildbranch-get-openapi.md
- name: App Veyor Parameters Projects Status Statusbadgeid Branch Buildbranch
  x-api-slug: app-veyor
  description: Parameters projects status statusbadgeid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{statusBadgeId}/branch/{buildBranch}
  tags: Projects,Status,StatusBadgeId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsstatusstatusbadgeidbranchbuildbranch-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Branch Buildbranch
  x-api-slug: app-veyor
  description: Get projects accountname projectslug branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/branch/{buildBranch}
  tags: Projects,AccountName,ProjectSlug,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugbranchbuildbranch-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Branch Buildbranch
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/branch/{buildBranch}
  tags: Projects,AccountName,ProjectSlug,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugbranchbuildbranch-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Build Buildversion
  x-api-slug: app-veyor
  description: Get projects accountname projectslug build buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/build/{buildVersion}
  tags: Projects,AccountName,ProjectSlug,Build,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildbuildversion-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Build Buildversion
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug build buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/build/{buildVersion}
  tags: Projects,AccountName,ProjectSlug,Build,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildbuildversion-parameters-openapi.md
- name: App Veyor Delete Projects Accountname Projectslug Buildcache
  x-api-slug: app-veyor
  description: Delete projects accountname projectslug buildcache.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/buildcache
  tags: Projects,AccountName,ProjectSlug,Buildcache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildcache-delete-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Buildcache
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug buildcache.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/buildcache
  tags: Projects,AccountName,ProjectSlug,Buildcache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildcache-parameters-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings Build Number
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings build number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/build-number
  tags: Projects,AccountName,ProjectSlug,Settings,Build,Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsbuildnumber-parameters-openapi.md
- name: App Veyor Put Projects Accountname Projectslug Settings Build Number
  x-api-slug: app-veyor
  description: Put projects accountname projectslug settings build number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/build-number
  tags: Projects,AccountName,ProjectSlug,Settings,Build,Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsbuildnumber-put-openapi.md
- name: App Veyor Get Projects Status Webhookid Branch Buildbranch
  x-api-slug: app-veyor
  description: Get projects status webhookid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{webhookId}/branch/{buildBranch}
  tags: Projects,Status,WebhookId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsstatuswebhookidbranchbuildbranch-get-openapi.md
- name: App Veyor Parameters Projects Status Webhookid Branch Buildbranch
  x-api-slug: app-veyor
  description: Parameters projects status webhookid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{webhookId}/branch/{buildBranch}
  tags: Projects,Status,WebhookId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/projectsstatuswebhookidbranchbuildbranch-parameters-openapi.md
- name: App Veyor
  x-api-slug: app-veyor
  description: We provide continuous integration tools for Windows developers. The
    service is offered for free to open-source projects, we offer subscriptions for
    private projects and AppVeyor Enterprise installations on customer premises.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api
  tags: Build
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/appveyor-ci/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/appveyor-systems-inc
- type: x-documentation
  url: https://www.appveyor.com/docs/
- type: x-email
  url: jobs@appveyor.com
- type: x-email
  url: team@appveyor.com
- type: x-email
  url: privacy@appveyor.com
- type: x-twitter
  url: https://twitter.com/appveyor
- type: x-website
  url: http://appveyor.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---