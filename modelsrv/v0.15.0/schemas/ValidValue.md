# ValidValue

A discrete, finite value that is valid for a Parameter.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the valid value.
- `displayName` (string, required) — The human-readable name of the value (e.g. "8GB", "10000-users").
- `parameter` (string (uuid), required) — The UUID of the Parameter this value belongs to.
- `validValueId` (string (uuid), required) — An UUID that uniquely identifies the valid value.

