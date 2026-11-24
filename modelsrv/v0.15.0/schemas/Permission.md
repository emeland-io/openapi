# Permission

Realized permission instance linked to a permission spec within the landscape.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md))
- `description` (string)
- `displayName` (string, required)
- `permissionId` (string (uuid), required)
- `spec` (string (uuid), required) — UUID of the PermissionSpec this permission realizes.

