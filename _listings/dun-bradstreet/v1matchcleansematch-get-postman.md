{
  "info": {
    "name": "D&B Direct+ Identity Resolution IDR Domain Email",
    "_postman_id": "85d67343-8e85-4dec-8ca5-2b84c7fd314e",
    "description": "Idr domain email.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Businesses",
      "item": [
        {
          "id": "44b63a23-061e-4d9c-a52e-6ffe4fc972e4",
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
              "id": "066c595a-846b-4825-af6d-1117e67487c1"
            }
          ]
        }
      ]
    }
  ]
}