# Route Stops

List of bus stops.

**URL** : `/route/info/{route_id}/stops`

**Method** : `GET`

**Auth required** : NO

**Data constraints** : NO

## Success Response

**Code** : `200 OK`

**Content example**

```json
{"error":"false","data":[  
   {  
      "id":397,
      "longitute":"-47.886266434136",
      "latitute":"-15.752832494602",
      "reference":"3196",
      "sequence":54,
      "locale":"ASA NORTE",
      "full_address":"ERL - Norte - Shcn - Asa Norte, Bras\u00edlia - DF, 70863-110, Brazil"
   },
   {  
      "id":405,
      "longitute":"-47.888256593580",
      "latitute":"-15.746633566135",
      "reference":"3285",
      "sequence":100,
      "locale":"ASA NORTE",
      "full_address":"ERL - Norte - Shcn - Asa Norte, Bras\u00edlia - DF, 70872-090, Brazil"
   },
   {  
      "id":401,
      "longitute":"-47.880389191307",
      "latitute":"-15.788884937563",
      "reference":"3463",
      "sequence":208,
      "locale":"BRAS\u00cdLIA",
      "full_address":"DF-002 - Bras\u00edlia, DF, 72010-120, Brazil"
   },
   {  
      "id":399,
      "longitute":"-47.880000405302",
      "latitute":"-15.778223942527",
      "reference":"3465",
      "sequence":209,
      "locale":"ASA NORTE",
      "full_address":"ERL - Norte - Shcn - Asa Norte, Bras\u00edlia - DF, 70833-110, Brazil"
   },
   {  
      "id":400,
      "longitute":"-47.880805785127",
      "latitute":"-15.771671200109",
      "reference":"3466",
      "sequence":210,
      "locale":"ASA NORTE",
      "full_address":"ERL - Norte - Shcn - Asa Norte, Bras\u00edlia - DF, 70843-070, Brazil"
   },
   {  
      "id":406,
      "longitute":"-47.890258479076",
      "latitute":"-15.740392355284",
      "reference":"3468",
      "sequence":211,
      "locale":"ASA NORTE",
      "full_address":"ERL - Norte - Shcn - Asa Norte, Bras\u00edlia - DF, 70874-070, Brazil"
   }
]}
```


## Error Response

**Condition** : If something is wrong.

**Code** : `400 BAD REQUEST`

**Content Example** :

```json
{  
   "error":"true",
   "message":"SQLSTATE[23000]: Integrity constraint violation"
}
```