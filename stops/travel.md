# Stops Travel

Information about travels in a bus stop.

**URL** : `/stops/{stops_id}/travel`

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
      "full_address":"Riacho Fundo II-1A Etapa Qn 8E Qn 7F - N\u00facleo Bandeirante - Riacho Fundo II, Bras\u00edlia - DF, 71880-160, Brazil",
      "travels":[  
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
         },
         {  
            "id":83,
            "rate":"5.00",
            "reference":"0.870",
            "description":"Recanto das Emas (Q. 800)\/ Riacho Fundo II\/ Rodovi\u00e1ria do Plano Piloto (Eixo)"
         },
         {  
            "id":137,
            "rate":"3.50",
            "reference":"805.7",
            "description":"Recanto das Emas (Riacho Fundo II) \/ \u00c1guas Claras"
         }
      ]
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