# Locale

List of locale.

**URL** : `/locale`

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
         "id":1,
         "name":"PLANALTINA",
         "description":"PLANALTINA - RA VI"
      },
      {  
         "id":2,
         "name":"S\u00c3O SEBASTI\u00c3O",
         "description":"S\u00c3O SEBASTI\u00c3O - R. A. XIV"
      },
      {  
         "id":3,
         "name":"SOBRADINHO",
         "description":"SOBRADINHO - RA V"
      },
      {  
         "id":4,
         "name":"SOBRADINHO II",
         "description":"SOBRADINHO II - RA XXVI"
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