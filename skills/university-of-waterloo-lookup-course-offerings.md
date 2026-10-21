---
name: lookup-course-offerings
description: Find a term, then list course offerings and class schedules for a subject.
api: courses
operations:
- getV3TermsCurrent
- getV3CoursesByTermCodeBySubject
- getV3ClassSchedulesByTermCodeBySubjectByCatalogNumber
generated: '2026-10-20'
method: generated
---

1. Call `getV3TermsCurrent`.
2. Call `getV3CoursesByTermCodeBySubject`.
3. Call `getV3ClassSchedulesByTermCodeBySubjectByCatalogNumber`.

All calls are GET with the `x-api-key` header; stay under 120 requests per minute. A 401 means a missing or revoked key.
