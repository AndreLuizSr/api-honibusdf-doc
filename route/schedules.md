# Route Schedules

List of bus route schedules.

**URL** : `/route/info/{route_id}/schedules`

**Method** : `GET`

**Auth required** : NO

**Data constraints** : NO

## Success Response

**Code** : `200 OK`

**Content example**

```json
{"error":"false","data":[
   {  
      "id":784,
      "route_id":6,
      "weekday":0,
      "hour":"08",
      "minute":"00",
      "hourminute":"08:00"
   },
   {  
      "id":785,
      "route_id":6,
      "weekday":1,
      "hour":"08",
      "minute":"00",
      "hourminute":"08:00"
   },
   {  
      "id":786,
      "route_id":6,
      "weekday":2,
      "hour":"08",
      "minute":"00",
      "hourminute":"08:00"
   },
   {  
      "id":787,
      "route_id":6,
      "weekday":3,
      "hour":"08",
      "minute":"00",
      "hourminute":"08:00"
   },
   {  
      "id":788,
      "route_id":6,
      "weekday":4,
      "hour":"08",
      "minute":"00",
      "hourminute":"08:00"
   }
]}
```

Weekday: Numeric representation of the day of the week  0 (for Sunday) through 6 (for Saturday)

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