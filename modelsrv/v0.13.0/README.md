# Emerging Enterprise Landscape API

API to query data collectors for an emerging enterprise landscape.

- **Release:** `v0.13.0`
- **API version:** `0.1.0`

## Servers

- `https://emeland.local/v1`

## Endpoints

- [landscape](endpoints/landscape.md) — query information to the landscape found.
- [p0_structure](endpoints/p0_structure.md) — endpoints for elements of the model pertaining to phase 0 of the EmELand model concerning contexts.
- [p1_structure](endpoints/p1_structure.md) — endpoints for elements of the model pertaining to phase 1 of the EmELand model concerning system structure, interfaces and system instances.
- [p3_capabilities](endpoints/p3_capabilities.md) — endpoints for elements of the model pertaining to phase 3 of the EmELand model concerning offered capabilities and orders to consume these capabilities.
- [p5_risk](endpoints/p5_risk.md) — endpoints for elements of the model pertaining to phase 5 of the EmELand model concerning managing risk and security.
- [p6_observability](endpoints/p6_observability.md) — endpoints for elements of the model pertaining to phase 6 of the EmELand model concerning observability, logging and monitoring.
- [p7_capacity](endpoints/p7_capacity.md) — endpoints for elements of the model pertaining to phase 7 of the EmELand model concerning capacity planing and management.
- [p8_data_catalog](endpoints/p8_data_catalog.md) — endpoints for elements of the model pertaining to phase 8 of the EmELand model concerning a data catalog.
- [events](endpoints/events.md) — register and query for events about changes in the landscape.
- [untagged](endpoints/untagged.md)

## Schemas

- [API](schemas/API.md)
- [Annotation](schemas/Annotation.md) — Represents a key-value pair used for annotating systems and other entities in the EmELand model.
- [ApiInstance](schemas/ApiInstance.md)
- [Artifact](schemas/Artifact.md) — Represents a binary artefact (e.g. software package, archive, binary executable) tracked in the landscape.
- [ArtifactInstance](schemas/ArtifactInstance.md) — Represents a specific instance (copy/location) of an Artifact.
- [Binding](schemas/Binding.md) — Binds a subject (group or identity) to a role.
- [BoundValue](schemas/BoundValue.md) — A BoundValue records a specific ValidValue chosen for a Parameter on an OrderItem.
- [Capability](schemas/Capability.md) — A capability represents a technical building block offered by a product or system.
- [CapabilityVersion](schemas/CapabilityVersion.md) — A versioned lifecycle of a Capability, with availability windows.
- [Capacity](schemas/Capacity.md) — Represents how much of a capacity resource type exists in a context, categorized as requested, provided, or consumed.
- [CapacityCategory](schemas/CapacityCategory.md) — Classification of how much capacity exists in a context.
- [CapacityContextRef](schemas/CapacityContextRef.md) — Reference to a Phase 0 context.
- [CapacityResourceType](schemas/CapacityResourceType.md) — Shared vocabulary for a measurable capacity limit with a unit.
- [CapacityResourceTypeRef](schemas/CapacityResourceTypeRef.md) — Reference to a capacity resource type vocabulary entry.
- [Component](schemas/Component.md)
- [ComponentInstance](schemas/ComponentInstance.md)
- [Context](schemas/Context.md) — Represents a context in the EmELand model.
- [ContextType](schemas/ContextType.md) — Represents a type of context in the EmELand model.
- [Dependency](schemas/Dependency.md) — A Dependency links a Variant to another Capability it needs, with optional ValidValue mappings.
- [ErrorString](schemas/ErrorString.md)
- [Event](schemas/Event.md) — Represents a change in the landscape model for event replication between servers.
- [FilterRule](schemas/FilterRule.md) — Documents a filter registered in a modelsrv instance.
- [Finding](schemas/Finding.md) — Represents the finding of a rule violation.
- [FindingType](schemas/FindingType.md) — Represents a type of findings in the EmELand model.
- [FindingTypeView](schemas/FindingTypeView.md) — A resolved finding type reference for read API responses.
- [FindingView](schemas/FindingView.md) — An enriched finding for read API responses with resolved type and resource references.
- [Group](schemas/Group.md) — Represents a group of identities in the EmELand model.
- [Identity](schemas/Identity.md) — Represents an identity in the EmELand model.
- [InstanceList](schemas/InstanceList.md)
- [InstanceListItem](schemas/InstanceListItem.md)
- [MergeRule](schemas/MergeRule.md) — Documents a merge rule registered in a modelsrv instance.
- [Metric](schemas/Metric.md) — Abstract measurement with business value.
- [MetricInstance](schemas/MetricInstance.md) — A concrete instantiation of a Metric bound to an optional subject (the resource the metric is measured for).
- [MetricInstanceRef](schemas/MetricInstanceRef.md) — Reference to a MetricInstance.
- [MetricRef](schemas/MetricRef.md) — Reference to a Metric vocabulary entry.
- [MetricValue](schemas/MetricValue.md) — Current reading of a MetricInstance.
- [Node](schemas/Node.md) — Represents a node in the EmELand model.
- [NodeSummaryView](schemas/NodeSummaryView.md) — An enriched node summary for read API list responses with resolved node type reference.
- [NodeType](schemas/NodeType.md) — Represents a type of node in the EmELand model.
- [NodeTypeView](schemas/NodeTypeView.md) — A resolved node type reference for read API responses.
- [NodeView](schemas/NodeView.md) — An enriched node for read API detail responses with resolved node type reference.
- [Order](schemas/Order.md) — An Order tracks Capabilities ordered by an OrgUnit after commercial processes complete.
- [OrderItem](schemas/OrderItem.md) — An OrderItem selects a Capability (version and variant) and binds Parameter values for an Order.
- [OrgUnit](schemas/OrgUnit.md) — Represents a organizational unit in the EmELand model.
- [Parameter](schemas/Parameter.md) — A parameter defines an identifier for a grouping of discrete ValidValues.
- [Permission](schemas/Permission.md) — Realized permission instance linked to a permission spec within the landscape.
- [PermissionSpec](schemas/PermissionSpec.md) — Organizational definition of a permission (spec / requirement).
- [Product](schemas/Product.md) — A product procured by the enterprise—software artefacts released together from the same legal or natural entity, optionally tied to an organizational vendor and versioned lifecycle windows.
- [ProductionVersion](schemas/ProductionVersion.md) — A software release line or cut of a product identified by lifecycle dates and constituent artefacts.
- [ResourceRef](schemas/ResourceRef.md)
- [ResourceView](schemas/ResourceView.md) — A resolved resource reference for read API responses.
- [Role](schemas/Role.md) — Realized role with spec reference, granted permissions, scope resources, and context.
- [RoleSpec](schemas/RoleSpec.md) — Organizational definition of a role referencing permission specs.
- [SubjectRef](schemas/SubjectRef.md) — Subject of a binding — either a group or an identity (mutually exclusive).
- [System](schemas/System.md) — Represents a system in the EmELand model.
- [SystemInstance](schemas/SystemInstance.md)
- [Threshold](schemas/Threshold.md) — Condition of arbitrary complexity attached to a MetricInstance.
- [ValidValue](schemas/ValidValue.md) — A discrete, finite value that is valid for a Parameter.
- [ValueMapping](schemas/ValueMapping.md) — Maps a ValidValue on the requiring side of a Dependency to a ValidValue on the depended-on Capability.
- [Variant](schemas/Variant.md) — A Variant models a dependency pattern for a CapabilityVersion under a set of required Parameter values.
- [Version](schemas/Version.md) — Version information for all objects in the EmELand model.
