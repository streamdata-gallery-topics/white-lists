swagger: "2.0"
x-collection-name: Click Meter
x-complete: 1
info:
  title: Click Meter
  description: api-dashboard-for-clickmeter-api
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