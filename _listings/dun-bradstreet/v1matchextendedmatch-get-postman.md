{
  "info": {
    "name": "D&B Direct+ Identity Resolution IDR & Append Domain URL",
    "_postman_id": "3783bce0-c445-4ac1-a7ca-2f9d4f623030",
    "description": "Idr & append domain url.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Businesses",
      "item": [
        {
          "id": "0f0383df-5a5c-4c6f-9c24-d9aa01508a5b",
          "name": "V1MatchCleanseMatchGet10",
          "request": {
            "url": "http://plus.dnb.com/v1/match/cleanseMatch?countryISOAlpha2Code=%7B%7D&email=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Idr domain email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e3e0e7d-8ae1-4bea-a354-9e1b51fe2223"
            }
          ]
        },
        {
          "id": "8fa836f8-ae9d-4066-9010-feed817efc8f",
          "name": "V1MatchExtendedMatchGet4",
          "request": {
            "url": "http://plus.dnb.com/v1/match/extendedMatch?countryISOAlpha2Code=%7B%7D&productId=%7B%7D&url=%7B%7D&versionId=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Idr & append domain url."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85822c78-b2f3-48d8-a575-6d51088cc884"
            }
          ]
        }
      ]
    }
  ]
}