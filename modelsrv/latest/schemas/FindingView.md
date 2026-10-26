# FindingView

An enriched finding for read API responses with resolved type and resource references.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the finding.
- `description` (string)
- `displayName` (string, required) — The human-readable name of the finding.
- `findingId` (string (uuid), required)
- `findingType` ([FindingTypeView](./FindingTypeView.md), required) — A resolved finding type reference for read API responses.
- `reference` (string (uri), required) — A URI reference to this finding.
- `resources` (array of [ResourceView](./ResourceView.md), required)

