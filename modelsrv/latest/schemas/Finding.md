# Finding

Represents the finding of a rule violation. Rules may either be defined for semantic correctness of the model or for compliance checks against external regulations and standards.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the finding.
- `description` (string)
- `displayName` (string, required) — The human-readable name of the finding.
- `findingId` (string (uuid), required)
- `resources` (array of [ResourceRef](./ResourceRef.md), required)
- `type` (string (uuid), required)

