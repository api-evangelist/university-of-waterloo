---
name: find-campus-location
description: Search campus buildings by name and return GeoJSON for mapping.
api: locations
operations:
- getV3LocationsSearchByLocationName
- getV3LocationsByLocationCodeGeojson
generated: '2026-10-20'
method: generated
---

1. Call `getV3LocationsSearchByLocationName`.
2. Call `getV3LocationsByLocationCodeGeojson`.

All calls are GET with the `x-api-key` header; stay under 120 requests per minute. A 401 means a missing or revoked key.
