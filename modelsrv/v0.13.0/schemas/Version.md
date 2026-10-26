# Version

Version information for all objects in the EmELand model.

- **Type:** object

## Properties

- `availableFrom` (string (date-time)) — Timestamp indicating when this version becomes available. Format is 2006-01-02. May be in the future
- `deprecatedFrom` (string (date-time)) — Timestamp indicating when this version is considered deprecated. Consumers should avoid using this version after this date. Format is 2006-01-02. May be in the future. Must be later than availableFrom.
- `terminatedFrom` (string (date-time)) — Timestamp indicating when this version is considered terminated. Consumers must not use this version after this date. Format is 2006-01-02. Must be later than deprecatedFrom.
- `version` (string, required) — Structured version string (e.g., "1.0.0"). The use of semantic versioning is recommended.

