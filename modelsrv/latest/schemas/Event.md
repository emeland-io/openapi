# Event

Represents a change in the landscape model for event replication between servers.

- **Type:** object

## Properties

- `kind` (string, required) — Discriminator for the replicated resource. Interpretation matches domain resource names (e.g. Node, Context, System, ApiInstance, OrgUnit). Subscribers unmarshal `resource` based on this value.
- `operation` (required) — The type of the event. Enum: `Unknown`, `Create`, `Update`, `Delete`.
- `resource` (object) — JSON object for create/update events. Shape aligns with the corresponding landscape GET entity response for that kind where one exists.
- `resourceId` (string (uuid)) — Set for delete events when no resource body is sent.

