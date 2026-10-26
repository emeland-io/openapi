# Binding

Binds a subject (group or identity) to a role.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md))
- `bindingId` (string (uuid), required)
- `description` (string)
- `displayName` (string, required)
- `role` (string (uuid), required)
- `subject` ([SubjectRef](./SubjectRef.md), required) — Subject of a binding — either a group or an identity (mutually exclusive).

