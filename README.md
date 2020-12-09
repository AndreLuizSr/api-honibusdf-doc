# ApiDocs

This API provide JSON responses for the service running on 'https://horariodeonibusdf.com.br/api'.

## Endpoints for Travels

* [All Travels](travel/default.md) : `GET /travel`

* [Travel Info](travel/info.md) : `GET /travel/{travel_id}`

* [Routes Info](travel/route.md) : `GET /travel/{travel_id}/route`

## Endpoints for Routes

* [Route Info](route/info.md) : `GET /route/{route_id}`

* [Track Info](route/track.md) : `GET /route/{route_id}/track`

* [Schedules Info](route/schedules.md) : `GET /route/{route_id}/schedules`

* [Stops Info](route/stops.md) : `GET /route/{route_id}/stops`

## Endpoints for Locale

* [Locales](locale/default.md) : `GET /locale`

* [Stops Info](locale/stops.md) : `GET /locale/{locale_id}/stops`

* [Stops Info](locale/travel.md) : `GET /locale/{locale_id}/travel`

## Endpoints for Bus Stop

* [Stop Info](stops/info.md) : `GET /stops/{stops_id}`

* [Travel Info](stops/travel.md) : `GET /stops/{stops_id}/travel`