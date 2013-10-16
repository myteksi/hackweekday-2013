## HACKWEEKDAY 2013 16th - 17th Oct 2013

### MyTeksi API
Please get your public key from us

**HOST**: test.grabtaxi.com

#### Sending alert
**POST**: `/api/public/v1/alerts/sos/`

**Request header**:
```
  Content-Type: application/json
  mts-public-key: "AXCTU8732HDBCJ8482XHJDFHJJ"
```

**Request parameters**:
```
{
    "title": "Please help!"
  , "message": "Help me please, there's too much goat cheese in my salad!"
  , "latitude": 3.10000
  , "longitude": 100.1000
}
```

**Responses**:

**Success**
```
{
    "status": 200
  , "code": 2001
  , "property": ""
  , "message": "Success"
  , "developerMessage": "No problems found :)"
}
```

**Failure**
```
{
    "status": 400
  , "code": 4001
  , "property": "title"
  , "message": "Unable to process your request"
  , "developerMessage": "Looks like the parameter 'title' is missing"
}
```
