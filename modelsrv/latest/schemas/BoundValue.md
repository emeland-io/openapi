# BoundValue

A BoundValue records a specific ValidValue chosen for a Parameter on an OrderItem.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the bound value.
- `boundValueId` (string (uuid), required) — An UUID that uniquely identifies the bound value.
- `displayName` (string, required) — The human-readable name of the bound value.
- `orderItem` (string (uuid), required) — The UUID of the OrderItem this binding belongs to.
- `parameter` (string (uuid), required) — The UUID of the Parameter being bound.
- `validValue` (string (uuid), required) — The UUID of the ValidValue selected for the Parameter.

