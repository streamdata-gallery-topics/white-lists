---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "10000"
tags: White Lists
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid - Delete Access Settings Whitelist
  x-api-slug: access-settingswhitelist-delete
  description: |-
    **This endpoint allows you to remove one or more IPs from your IP whitelist.**

    You can remove one IP at a time, or you can remove multiple IP addresses.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/access-settingswhitelist-delete-openapi.md
- name: SendGrid - Get Access Settings Whitelist
  x-api-slug: access-settingswhitelist-get
  description: |-
    **This endpoint allows you to retrieve a list of IP addresses that are currently whitelisted.**

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/access-settingswhitelist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/access-settingswhitelist-get-openapi.md
- name: SendGrid - Add Access Settings Whitelist
  x-api-slug: access-settingswhitelist-post
  description: |-
    **This endpoint allows you to add one or more IP addresses to your IP whitelist.**

    When adding an IP to your whitelist, include the IP address in an array. You can whitelist one IP at a time, or you can whitelist multiple IPs at once.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/access-settingswhitelist-post-openapi.md
- name: SendGrid - Delete Access Settings Whitelist Rule
  x-api-slug: access-settingswhitelistrule-id-delete
  description: |-
    **This endpoint allows you to remove a specific IP address from your IP whitelist.**

    When removing a specific IP address from your whitelist, you must include the ID in your call.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/access-settingswhitelistrule-id-delete-openapi.md
- name: SendGrid - Get Access Settings Whitelist Rule
  x-api-slug: access-settingswhitelistrule-id-get
  description: |-
    **This endpoint allows you to retreive a specific IP address that has been whitelisted.**

    You must include the ID for the specific IP address you want to retrieve in your call.

    IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.

    For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/access-settingswhitelistrule-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/access-settingswhitelistrule-id-get-openapi.md
- name: SendGrid - Get Mail Settings Address Whitelist
  x-api-slug: mail-settingsaddress-whitelist-get
  description: |-
    **This endpoint allows you to retrieve your current email address whitelist settings.**

    The address whitelist setting whitelists a specified email address or domain for which mail should never be suppressed. For example, you own the domain ???example.com,??? and one or more of your recipients use email@example.com addresses, by placing example.com in the address whitelist setting, all bounces, blocks, and unsubscribes logged for that domain will be ignored and sent as if under normal sending conditions.

    Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid???s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/mail-settingsaddress-whitelist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/mail-settingsaddress-whitelist-get-openapi.md
- name: SendGrid - Patch Mail Settings Address Whitelist
  x-api-slug: mail-settingsaddress-whitelist-patch
  description: |-
    **This endpoint allows you to update your current email address whitelist settings.**

    The address whitelist setting whitelists a specified email address or domain for which mail should never be suppressed. For example, you own the domain ???example.com,??? and one or more of your recipients use email@example.com addresses, by placing example.com in the address whitelist setting, all bounces, blocks, and unsubscribes logged for that domain will be ignored and sent as if under normal sending conditions.

    Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid???s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/white-lists/master/_listings/sendgrid/mail-settingsaddress-whitelist-patch-openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-api-gallery
  url: http://school.digger.api.gallery.streamdata.io
- type: x-api-stack
  url: http://sendgrid.stack.network
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-crunchbase
  url: https://crunchbase.com/organization/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-email
  url: privacy@sendgrid.com
- type: x-email
  url: legal@sendgrid.com
- type: x-email
  url: dpo@sendgrid.com
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-linkedin
  url: https://www.linkedin.com/company/sendgrid
- type: x-node-js-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: http://sendgrid.com
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---