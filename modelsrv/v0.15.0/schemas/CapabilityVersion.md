# CapabilityVersion

A versioned lifecycle of a Capability, with availability windows.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the capability version.
- `capability` (string (uuid), required) — The UUID of the Capability this version belongs to.
- `capabilityVersionId` (string (uuid), required) — An UUID that uniquely identifies the capability version.
- `displayName` (string, required) — The human-readable name of the capability version.
- `version` ([Version](./Version.md)) — Version information for all objects in the EmELand model.

