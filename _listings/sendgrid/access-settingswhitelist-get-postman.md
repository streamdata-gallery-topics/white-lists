{
  "info": {
    "name": "SendGrid Get Access Settings Whitelist",
    "_postman_id": "e95d1303-36e7-4464-8e61-1faabfc47b3f",
    "description": "**This endpoint allows you to retrieve a list of IP addresses that are currently whitelisted.**\n\nIP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.\n\nFor more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "email",
      "item": [
        {
          "id": "d23b544e-46e6-432e-b1d1-01261fcf9c64",
          "name": "access_settings.whitelist.get",
          "request": {
            "url": "http://api.sendgrid.com/v3/access_settings/whitelist?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**This endpoint allows you to retrieve a list of IP addresses that are currently whitelisted"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd3f9d54-e536-48d2-ae8e-08d2ee94b869"
            }
          ]
        }
      ]
    }
  ]
}