# Order

An Order tracks Capabilities ordered by an OrgUnit after commercial processes complete.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the order.
- `displayName` (string, required) — The human-readable name of the order.
- `orderId` (string (uuid), required) — An UUID that uniquely identifies the order.
- `orgUnit` (string (uuid), required) — The UUID of the OrgUnit that placed the order.

