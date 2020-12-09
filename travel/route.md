# Travel Routes

List routes of buses.

**URL** : `/travel/{travel_id}/routes`

**Method** : `GET`

**Auth required** : NO

**Data constraints** : NO

## Success Response

**Code** : `200 OK`

**Content example**

```json
{"error":"false","data":[    
   {  
      "id":2,
      "origin":"SOBRADINHO (QUADRA 18)",
      "destination":"ESTA\u00c7\u00c3O DO METR\u00d4 (ASA SUL)",
      "direction":"IDA"
   },
   {  
      "id":3,
      "origin":"ESTA\u00c7\u00c3O DO METR\u00d4 (ASA SUL)",
      "destination":"SOBRADINHO (QUADRA 18)",
      "direction":"VOLTA"
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