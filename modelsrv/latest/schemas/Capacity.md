# Capacity

Represents how much of a capacity resource type exists in a context, categorized as requested, provided, or consumed.

- **Type:** object

## Properties

- `amount` (string, required) — Non-negative decimal quantity of the capacity resource type in this context and category.
- `annotations` (array of [Annotation](./Annotation.md)) — Extended metadata for the capacity entry.
- `capacityId` (string (uuid), required)
- `category` ([CapacityCategory](./CapacityCategory.md), required) — Classification of how much capacity exists in a context.
- `contextRef` ([CapacityContextRef](./CapacityContextRef.md), required) — Reference to a Phase 0 context.
- `description` (string) — A brief description of the capacity entry.
- `displayName` (string, required) — The human-readable name of the capacity entry.
- `resourceTypeRef` ([CapacityResourceTypeRef](./CapacityResourceTypeRef.md), required) — Reference to a capacity resource type vocabulary entry.

