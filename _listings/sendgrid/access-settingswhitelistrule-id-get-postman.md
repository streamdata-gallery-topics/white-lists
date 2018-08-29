{
  "info": {
    "name": "SendGrid Get Access Settings Whitelist Rule",
    "_postman_id": "3813333e-2ec9-47d9-9014-c66251d8b7e1",
    "description": "**This endpoint allows you to retreive a specific IP address that has been whitelisted.**\n\nYou must include the ID for the specific IP address you want to retrieve in your call.\n\nIP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.\n\nFor more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "email",
      "item": [
        {
          "id": "9ee270f7-d120-4200-a685-72af7b6b70f8",
          "name": "access_settings.whitelist.rule_id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.sendgrid.com",
              "path": [
                "v3",
                "access_settings/whitelist/:rule_id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "rule_id",
                  "value": "rule_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**This endpoint allows you to retreive a specific IP address that has been whitelisted"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0995ac8d-d7a3-4a73-aaca-303079d588b0"
            }
          ]
        }
      ]
    }
  ]
}