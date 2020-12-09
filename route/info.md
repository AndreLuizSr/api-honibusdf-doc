# Route Info

Information about route.

**URL** : `/route/{route_id}`

**Method** : `GET`

**Auth required** : NO

**Data constraints** : NO

## Success Response

**Code** : `200 OK`

**Content example**

```json
{"error":"false","data":{  
   "id":2,
   "origin":"SOBRADINHO (QUADRA 18)",
   "destination":"ESTA\u00c7\u00c3O DO METR\u00d4 (ASA SUL)",
   "direction":"IDA"
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