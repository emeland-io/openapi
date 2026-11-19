# ResourceView

A resolved resource reference for read API responses.

- **Type:** object

## Properties

- `displayName` (string) — The human-readable name of the resource referenced.
- `id` (string (uuid), required) — The UUID of the resource referenced.
- `resourceType` (required) — The type of the resource referenced. Enum: `Context`, `ContextType`, `Node`, `NodeType`, `System`, `SystemInstance`, `API`, `ApiInstance`, `Component`, `ComponentInstance`, `Identity`, `OrgUnit`, `Group`, `Binding`, `RoleSpec`, `PermissionSpec`, `Role`, `Permission`, `Product`, `Finding`, `FindingType`, `Artifact`, `ArtifactInstance`, `FilterRule`, `MergeRule`, `Capability`, `Parameter`, `ValidValue`, `CapabilityVersion`, `Variant`, `Dependency`, `Order`, `OrderItem`, `BoundValue`, `Capacity`, `CapacityResourceType`, `Metric`, `Threshold`, `MetricInstance`, `MetricValue`.

