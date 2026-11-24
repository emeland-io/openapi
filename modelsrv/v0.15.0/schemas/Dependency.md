# Dependency

A Dependency links a Variant to another Capability it needs, with optional ValidValue mappings.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the dependency.
- `capability` (string (uuid), required) — The UUID of the Capability this dependency requires.
- `dependencyId` (string (uuid), required) — An UUID that uniquely identifies the dependency.
- `displayName` (string, required) — The human-readable name of the dependency.
- `mappings` (array of [ValueMapping](./ValueMapping.md)) — Mappings of ValidValues from the variant to the depended-on Capability.
- `variant` (string (uuid), required) — The UUID of the Variant that owns this dependency.

