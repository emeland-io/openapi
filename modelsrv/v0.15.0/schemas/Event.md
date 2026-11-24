# Event

Represents a change in the landscape model for event replication between servers.

- **Type:** object

## Properties

- `kind` (string, required) — Discriminator for the replicated resource. Interpretation matches domain resource names (e.g. Node, Context, System, ApiInstance, OrgUnit). Subscribers unmarshal `resource` based on this value.
- `operation` (required) — The type of the event. Enum: `Unknown`, `Create`, `Update`, `Delete`.
- `originUrl` (string, required) — Base API URL of the node that first produced this event. Stamped once at the origin node and preserved unchanged across every forwarding hop, so a receiver can always tell which node produced the change regardless of how many relays it passed through.
- `resource` (object) — JSON object for create/update events. Shape aligns with the corresponding landscape GET entity response for that kind where one exists.
- `resourceId` (string (uuid)) — Set for delete events when no resource body is sent.
- `timestamp` (string (date-time), required) — Time at which the origin node produced this event. Like originUrl it is stamped once at the origin and preserved across forwarding.

