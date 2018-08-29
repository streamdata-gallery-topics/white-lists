---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Delete an domain entry
  description: Delete an domain entry.
  contact:
    name: Api Support
    url: http://www.clickmeter.com/api
    email: api@clickmeter.com
  version: v2
host: apiv2.clickmeter.com:80
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/domainwhitelist/{whitelistId}:
    delete:
      summary: Delete an domain entry
      description: Delete an domain entry.
      operationId: deleteAccountDomainwhitelistWhitelist
      x-api-path-slug: accountdomainwhitelistwhitelistid-delete
      parameters:
      - in: path
        name: whitelistId
        description: The id of the domain to delete
      responses:
        200:
          description: OK
      tags:
      - Account
      - Domainwhitelist
      - WhitelistId
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