# Role

Realized role with spec reference, granted permissions, scope resources, and context.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md))
- `context` (string (uuid), required) — UUID of the Context where this role applies.
- `description` (string)
- `displayName` (string, required)
- `permissions` (array of string (uuid))
- `resources` (array of [ResourceRef](./ResourceRef.md))
- `roleId` (string (uuid), required)
- `spec` (string (uuid), required) — UUID of the RoleSpec this role realizes.

