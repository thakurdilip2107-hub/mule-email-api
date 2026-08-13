# mule-email-api
**Default branch:** `main` | **Scenario:** already has NEW pattern

| Field | Value |
|-------|-------|
| Default branch | `main` |
| log4j pattern | NEW `%d{ISO8601} %-5level [%thread] %logger{36} - %msg%n` |
| Expected result | `SKIPPED` — already up-to-date (idempotent) |
