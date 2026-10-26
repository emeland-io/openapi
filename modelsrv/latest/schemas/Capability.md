# Capability

A capability represents a technical building block offered by a product or system.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the capability.
- `capabilityId` (string (uuid), required) — An UUID that uniquely identifies the capability.
- `displayName` (string, required) — The human-readable name of the capability.
- `offers` (array of string (uuid)) — ValidValue UUIDs this capability offers (a subset of its Parameters' values).

