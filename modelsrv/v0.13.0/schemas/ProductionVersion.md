# ProductionVersion

A software release line or cut of a product identified by lifecycle dates and constituent artefacts.

- **Type:** object

## Properties

- `artefacts` (array of string (uuid)) — Identifiers of artefacts that belong to this release line together.
- `availableFrom` (string (date-time)) — When this release line becomes available for use.
- `deprecatedFrom` (string (date-time)) — When consumers should begin migrating away from this release line.
- `terminatedFrom` (string (date-time)) — After this time the release line must not be used for new workloads.

