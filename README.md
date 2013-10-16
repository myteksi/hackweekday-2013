## HACKWEEKDAY 2013 16th - 17th Oct 2013

### MyTeksi API
Please get your access token from us


#### Sending alert
POST: `/api/public/v1/alerts/sos/`

Request header:
```
  Content-Type: application/json
  mts-public-key: "AXCTU8732HDBCJ8482XHJDFHJJ"
```

Request parameters:
```
{
    "message": "Hello there"
  , "latitude": 3.10000
  , "longitude": 100.1000
}
```

Responses:

Success
```
{
    "status": 200
}
```

Failure
```
{
    "status": 400
  , "code": 4003
  , "property": ""
  , "message": ""
  , "developerMessage": ""
}
```
