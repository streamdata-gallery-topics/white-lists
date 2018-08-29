{
  "info": {
    "name": "SendGrid Get Mail Settings Address Whitelist",
    "_postman_id": "5bc57628-0fed-475b-b306-f7202d3c7936",
    "description": "**This endpoint allows you to retrieve your current email address whitelist settings.**\n\nThe address whitelist setting whitelists a specified email address or domain for which mail should never be suppressed. For example, you own the domain ???example.com,??? and one or more of your recipients use email@example.com addresses, by placing example.com in the address whitelist setting, all bounces, blocks, and unsubscribes logged for that domain will be ignored and sent as if under normal sending conditions.\n\nMail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid???s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "email",
      "item": [
        {
          "id": "09bd6542-e5cf-47b7-9baf-1300cb7903d0",
          "name": "mail_settings.address_whitelist.get",
          "request": {
            "url": "http://api.sendgrid.com/v3/mail_settings/address_whitelist?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**This endpoint allows you to retrieve your current email address whitelist settings"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2f60ca3-aba8-476f-84e0-18b194027c81"
            }
          ]
        }
      ]
    }
  ]
}