# Stops Info

Information about bus stop.

**URL** : `/stops/{stops_id}`

**Method** : `GET`

**Auth required** : NO

**Data constraints** : NO

## Success Response

**Code** : `200 OK`

**Content example**

```json
{  
   "error":"false",
   "data":{  
      "id":1390,
      "longitute":"-48.046349348017",
      "latitute":"-15.900324751155",
      "reference":"4010",
      "locale":"RIACHO FUNDO II",
      "full_address":"Riacho Fundo II-1A Etapa Qn 8E Qn 7F - N\u00facleo Bandeirante - Riacho Fundo II, Bras\u00edlia - DF, 71880-160, Brazil"
   }
}
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