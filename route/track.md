# Route - Track

List of places.

**URL** : `/route/info/{route_id}/track`

**Method** : `GET`

**Auth required** : NO

**Data constraints** : NO

## Success Response

**Code** : `200 OK`

**Content example**

```json
{"error":"false","data":[
   {
      "id":175,
      "route_id":6,
      "sequence":1,
      "description":"Rodovi\u00e1ria de Planaltina \/ RA VI",
      "locale":"PLANALTINA"
   },
   {
      "id":176,
      "route_id":6,
      "sequence":2,
      "description":"Avenida Independ\u00eancia \/ RA VI",
      "locale":"PLANALTINA"
   },
   {
      "id":177,
      "route_id":6,
      "sequence":3,
      "description":"Viaduto - Avenida Independ\u00eancia (Viaduto BR-020 sobre Av Independ\u00eancia) \/ RA VI",
      "locale":"PLANALTINA"
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