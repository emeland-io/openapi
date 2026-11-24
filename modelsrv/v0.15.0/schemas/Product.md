# Product

A product procured by the enterprise—software artefacts released together from the same legal or natural entity, optionally tied to an organizational vendor and versioned lifecycle windows.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the product.
- `description` (string) — A brief description of the product.
- `displayName` (string, required) — The human-readable name of the product.
- `productId` (string (uuid), required) — An UUID that uniquely identifies the product in the landscape.
- `vendor` (string (uuid)) — The UUID of the organizational unit acting as vendor or supplier for this product.
- `versions` (array of [ProductionVersion](./ProductionVersion.md)) — Lifecycle windows for lines of artefacts released together under this product.

