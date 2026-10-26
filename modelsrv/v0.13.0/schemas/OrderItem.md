# OrderItem

An OrderItem selects a Capability (version and variant) and binds Parameter values for an Order.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the order item.
- `capability` (string (uuid), required) — The UUID of the Capability being ordered.
- `capabilityVersion` (string (uuid), required) — The UUID of the CapabilityVersion being ordered.
- `contexts` (array of string (uuid)) — Context UUIDs in which this order item is fulfilled.
- `displayName` (string, required) — The human-readable name of the order item.
- `order` (string (uuid), required) — The UUID of the Order this item belongs to.
- `orderItemId` (string (uuid), required) — An UUID that uniquely identifies the order item.
- `variant` (string (uuid), required) — The UUID of the Variant selected for this order item.

