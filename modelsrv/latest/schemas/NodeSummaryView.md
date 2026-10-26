# NodeSummaryView

An enriched node summary for read API list responses with resolved node type reference.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the node.
- `description` (string) — A human-readable description of the node.
- `displayName` (string, required) — The human-readable name of the node.
- `nodeId` (string (uuid), required)
- `nodeType` ([NodeTypeView](./NodeTypeView.md), required) — A resolved node type reference for read API responses.
- `reference` (string (uri), required) — A URI reference to this node.

