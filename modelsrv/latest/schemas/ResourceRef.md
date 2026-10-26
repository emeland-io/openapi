# ResourceRef

- **Type:** object

## Properties

- `reference` (string (uri)) — A URI reference to the resource.
- `resourceId` (string (uuid), required) — The UUID of the resource referenced.
- `resourceType` (required) — The type of the resource referenced. Enum: `Context`, `ContextType`, `Node`, `NodeType`, `System`, `SystemInstance`, `API`, `ApiInstance`, `Component`, `ComponentInstance`, `Identity`, `OrgUnit`, `Group`, `Binding`, `RoleSpec`, `PermissionSpec`, `Role`, `Permission`, `Product`, `Finding`, `FindingType`, `Artifact`, `ArtifactInstance`, `FilterRule`, `MergeRule`, `Capability`, `Parameter`, `ValidValue`, `CapabilityVersion`, `Variant`, `Dependency`, `Order`, `OrderItem`, `BoundValue`, `Capacity`, `CapacityResourceType`, `Metric`, `Threshold`, `MetricInstance`, `MetricValue`.

