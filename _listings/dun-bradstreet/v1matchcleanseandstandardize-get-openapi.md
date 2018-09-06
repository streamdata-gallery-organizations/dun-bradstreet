---
swagger: "2.0"
x-collection-name: Dun & Bradstreet
x-complete: 0
info:
  title: D&B Direct+ Identity Resolution Cleanse & Standardize
  description: Cleanse & standardize.
  version: 1.0.0
host: plus.dnb.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/match/cleanseMatch:
    get:
      summary: IDR Domain Email
      description: Idr domain email.
      operationId: V1MatchCleanseMatchGet10
      x-api-path-slug: v1matchcleansematch-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: countryISOAlpha2Code
      - in: query
        name: email
      responses:
        200:
          description: OK
      tags:
      - Businesses
      - Domain
      - Email
  /v1/match/extendedMatch:
    get:
      summary: IDR & Append Domain URL
      description: Idr & append domain url.
      operationId: V1MatchExtendedMatchGet4
      x-api-path-slug: v1matchextendedmatch-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: countryISOAlpha2Code
      - in: query
        name: productId
      - in: query
        name: url
      - in: query
        name: versionId
      responses:
        200:
          description: OK
      tags:
      - Businesses
      - Append
      - Domain
      - URL
  /v2/token:
    post:
      summary: Authentication - Access Token
      description: Authentication - access token.
      operationId: V2TokenPost
      x-api-path-slug: v2token-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Businesses
      - Authentication
      - Access
      - Token
  /v1/match/cleanseAndStandardize:
    get:
      summary: Cleanse & Standardize
      description: Cleanse & standardize.
      operationId: V1MatchCleanseAndStandardizeGet
      x-api-path-slug: v1matchcleanseandstandardize-get
      parameters:
      - in: query
        name: addressLocality
      - in: query
        name: addressRegion
      - in: query
        name: countryISOAlpha2Code
      - in: query
        name: name
      - in: query
        name: streetAddressLine1
      responses:
        200:
          description: OK
      tags:
      - Businesses
      - Cleanse
      - Standardize
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