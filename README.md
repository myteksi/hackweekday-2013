## HACKWEEKDAY 2013 16th - 17th Oct 2013

### MyTeksi API
Please get your access token from us


#### Sending alert
URL: `/api/public/v1/alers/sos/`

Request header:
```
  Something should go in here ...
```

Request parameters:
```
{
  message: "Hello there"
}
```

Response:

Success
```
{
    "status": 200
}
```

```
{
    "status": 400
  , "code": 4003
  , "property": ""
  , "message": ""
  , "developerMessage": ""
}
```
