# Locale Travels

List of travels.

**URL** : `/locale/{route_id}/travel`

**Method** : `GET`

**Auth required** : NO

**Data constraints** : NO

## Success Response

**Code** : `200 OK`

**Content example**

```json
{  
   "error":"false",
   "data":[  
      {  
         "id":1247,
         "longitute":"-48.047987563425",
         "latitute":"-15.876264185371",
         "reference":"4018",
         "full_address":"EPCT - Riacho Fundo II, Bras\u00edlia - DF, 70297-400, Brazil"
      },
      {  
         "id":1248,
         "longitute":"-48.052144164194",
         "latitute":"-15.879045439170",
         "reference":"4017",
         "full_address":"EPCT - Riacho Fundo II, Bras\u00edlia - DF, 70297-400, Brazil"
      },
      {  
         "id":1249,
         "longitute":"-48.043659802360",
         "latitute":"-15.874219321304",
         "reference":"4019",
         "full_address":"EPCT - Riacho Fundo II, Bras\u00edlia - DF, 70297-400, Brazil"
      }
   ]
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