# Variant

A Variant models a dependency pattern for a CapabilityVersion under a set of required Parameter values.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the variant.
- `capabilityVersion` (string (uuid), required) — The UUID of the CapabilityVersion this variant belongs to.
- `displayName` (string, required) — The human-readable name of the variant.
- `requires` (array of string (uuid)) — ValidValue UUIDs this variant requires from its Parameters.
- `variantId` (string (uuid), required) — An UUID that uniquely identifies the variant.

