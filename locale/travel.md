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
         "id":18,
         "rate":"5.00",
         "reference":"813.2",
         "description":"Recanto das Emas (EPNB - EPIA) \/  W3 Sul - Norte"
      },
      {  
         "id":21,
         "rate":"3.50",
         "reference":"872.5",
         "description":"Recanto das Emas (Q 300-500)\/ Taguacenter (Feira dos Goianos)"
      },
      {  
         "id":28,
         "rate":"5.00",
         "reference":"0.817",
         "description":"Taguatinga Norte \/ Samambaia Sul \/ Recanto das Emas (Q.800) \/ Riacho Fundo II (QS 18)"
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