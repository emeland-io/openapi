# landscape

query information to the landscape found.

### GET `/landscape/api-instances`

Retrieve all API instances in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/api-instances/{apiInstanceId}`

Retrieve details of a specific API instance by its UUID.

**Parameters**

- `apiInstanceId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [ApiInstance](../schemas/ApiInstance.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/apis`

Retrieve all APIs in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/apis/{apiId}`

Retrieve details of a specific API by its UUID.

**Parameters**

- `apiId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [API](../schemas/API.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/artifactInstances`

Retrieve all artifact instances in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/artifactInstances/{artifactInstanceId}`

Retrieve details of a specific artifact instance by its UUID.

**Parameters**

- `artifactInstanceId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [ArtifactInstance](../schemas/ArtifactInstance.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/artifacts`

Retrieve all artifacts in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/artifacts/{artifactId}`

Retrieve details of a specific artifact by its UUID.

**Parameters**

- `artifactId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Artifact](../schemas/Artifact.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/bindings`

Retrieve all bindings in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/bindings/{bindingId}`

Retrieve details of a specific binding by its UUID.

**Parameters**

- `bindingId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Binding](../schemas/Binding.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/boundValues`

Retrieve all bound values registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [BoundValue](../schemas/BoundValue.md)

### GET `/landscape/boundValues/{boundValueId}`

Retrieve a bound value by its UUID.

**Parameters**

- `boundValueId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [BoundValue](../schemas/BoundValue.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/capabilities`

Retrieve all capabilities registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [Capability](../schemas/Capability.md)

### GET `/landscape/capabilities/{capabilityId}`

Retrieve a capability by its UUID.

**Parameters**

- `capabilityId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Capability](../schemas/Capability.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/capabilityVersions`

Retrieve all capability versions registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [CapabilityVersion](../schemas/CapabilityVersion.md)

### GET `/landscape/capabilityVersions/{capabilityVersionId}`

Retrieve a capability version by its UUID.

**Parameters**

- `capabilityVersionId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [CapabilityVersion](../schemas/CapabilityVersion.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/capacities`

Retrieve all capacity entries in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/capacities/{capacityId}`

Retrieve details of a specific capacity entry by its UUID.

**Parameters**

- `capacityId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Capacity](../schemas/Capacity.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/capacityResourceTypes`

Retrieve all capacity resource types in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/capacityResourceTypes/{capacityResourceTypeId}`

Retrieve details of a specific capacity resource type by its UUID.

**Parameters**

- `capacityResourceTypeId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [CapacityResourceType](../schemas/CapacityResourceType.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/component-instances`

Retrieve all component instances in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/component-instances/{componentInstanceId}`

Retrieve details of a specific component instance by its UUID.

**Parameters**

- `componentInstanceId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [ComponentInstance](../schemas/ComponentInstance.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/components`

Retrieve all components in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/components/{componentId}`

Retrieve details of a specific component by its UUID.

**Parameters**

- `componentId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Component](../schemas/Component.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/contextTypes`

Retrieve all context types in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/contextTypes/{contextTypeId}`

Retrieve details of a specific context type by its UUID.

**Parameters**

- `contextTypeId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [ContextType](../schemas/ContextType.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/contexts`

Retrieve all contexts in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/contexts/{contextId}`

Retrieve details of a specific context by its UUID.

**Parameters**

- `contextId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Context](../schemas/Context.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/dependencies`

Retrieve all dependencies registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [Dependency](../schemas/Dependency.md)

### GET `/landscape/dependencies/{dependencyId}`

Retrieve a dependency by its UUID.

**Parameters**

- `dependencyId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Dependency](../schemas/Dependency.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/filter-rules`

Retrieve all filter rules registered in this modelsrv instance.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/filter-rules/{ruleId}`

Retrieve a filter rule by its UUID.

**Parameters**

- `ruleId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [FilterRule](../schemas/FilterRule.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/findingTypes`

Retrieve all types of findings known to the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [FindingType](../schemas/FindingType.md)

### GET `/landscape/findingTypes/{findingTypeId}`

Retrieve a known types of findings by its UUID.

**Parameters**

- `findingTypeId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [FindingType](../schemas/FindingType.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/findings`

Retrieve all findings in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [FindingView](../schemas/FindingView.md)

### GET `/landscape/findings/{findingId}`

Retrieve details of a specific finding by its UUID.

**Parameters**

- `findingId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [FindingView](../schemas/FindingView.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/groups`

Retrieve all groups in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/groups/{groupId}`

Retrieve details of a specific group by its UUID.

**Parameters**

- `groupId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Group](../schemas/Group.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/identities`

Retrieve all identities in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/identities/{identityId}`

Retrieve details of a specific identity by its UUID.

**Parameters**

- `identityId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Identity](../schemas/Identity.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/merge-rules`

Retrieve all merge rules registered in this modelsrv instance.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/merge-rules/{ruleId}`

Retrieve a merge rule by its UUID.

**Parameters**

- `ruleId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [MergeRule](../schemas/MergeRule.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/metricInstances`

Retrieve all metric instances in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/metricInstances/{metricInstanceId}`

Retrieve details of a specific metric instance by its UUID.

**Parameters**

- `metricInstanceId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [MetricInstance](../schemas/MetricInstance.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/metricValues`

Retrieve all metric values in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/metricValues/{metricValueId}`

Retrieve details of a specific metric value by its UUID.

**Parameters**

- `metricValueId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [MetricValue](../schemas/MetricValue.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/metrics`

Retrieve all metrics in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/metrics/{metricId}`

Retrieve details of a specific metric by its UUID.

**Parameters**

- `metricId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Metric](../schemas/Metric.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/nodeTypes`

Retrieve all node types in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/nodeTypes/{nodeTypeId}`

Retrieve details of a specific node type by its UUID.

**Parameters**

- `nodeTypeId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [NodeType](../schemas/NodeType.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/nodes`

Retrieve all nodes in the landscape discovered so far.

**Responses**

- `200` — OK
  - `application/json`: array of [NodeSummaryView](../schemas/NodeSummaryView.md)

### GET `/landscape/nodes/{nodeId}`

Retrieve details of a specific node by its UUID.

**Parameters**

- `nodeId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [NodeView](../schemas/NodeView.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/orderItems`

Retrieve all order items registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [OrderItem](../schemas/OrderItem.md)

### GET `/landscape/orderItems/{orderItemId}`

Retrieve an order item by its UUID.

**Parameters**

- `orderItemId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [OrderItem](../schemas/OrderItem.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/orders`

Retrieve all orders registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [Order](../schemas/Order.md)

### GET `/landscape/orders/{orderId}`

Retrieve an order by its UUID.

**Parameters**

- `orderId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Order](../schemas/Order.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/orgUnits`

Retrieve all org units in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/orgUnits/{orgUnitId}`

Retrieve details of a specific org unit by its UUID.

**Parameters**

- `orgUnitId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [OrgUnit](../schemas/OrgUnit.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/parameters`

Retrieve all parameters registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [Parameter](../schemas/Parameter.md)

### GET `/landscape/parameters/{parameterId}`

Retrieve a parameter by its UUID.

**Parameters**

- `parameterId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Parameter](../schemas/Parameter.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/permissionSpecs`

Retrieve all permission specifications in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/permissionSpecs/{permissionSpecId}`

Retrieve details of a specific permission specification by its UUID.

**Parameters**

- `permissionSpecId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [PermissionSpec](../schemas/PermissionSpec.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/permissions`

Retrieve all realized permissions in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/permissions/{permissionId}`

Retrieve details of a specific permission by its UUID.

**Parameters**

- `permissionId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Permission](../schemas/Permission.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/products`

Retrieve all externally procured products tracked in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/products/{productId}`

Retrieve details of a specific product by its UUID.

**Parameters**

- `productId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Product](../schemas/Product.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/roleSpecs`

Retrieve all role specifications in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/roleSpecs/{roleSpecId}`

Retrieve details of a specific role specification by its UUID.

**Parameters**

- `roleSpecId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [RoleSpec](../schemas/RoleSpec.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/roles`

Retrieve all realized roles in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/roles/{roleId}`

Retrieve details of a specific role by its UUID.

**Parameters**

- `roleId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Role](../schemas/Role.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/system-instances`

Retrieve all system instances in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/system-instances/{systemInstanceId}`

Retrieve details of a specific system instance by its UUID.

**Parameters**

- `systemInstanceId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [SystemInstance](../schemas/SystemInstance.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/systems`

Retrieve all systems in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/systems/{systemId}`

Retrieve details of a specific system by its UUID.

**Parameters**

- `systemId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [System](../schemas/System.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/thresholds`

Retrieve all thresholds in the landscape.

**Responses**

- `200` — OK
  - `application/json`: [InstanceList](../schemas/InstanceList.md)

### GET `/landscape/thresholds/{thresholdId}`

Retrieve details of a specific threshold by its UUID.

**Parameters**

- `thresholdId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Threshold](../schemas/Threshold.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/validValues`

Retrieve all valid values registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [ValidValue](../schemas/ValidValue.md)

### GET `/landscape/validValues/{validValueId}`

Retrieve a valid value by its UUID.

**Parameters**

- `validValueId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [ValidValue](../schemas/ValidValue.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### GET `/landscape/variants`

Retrieve all variants registered in the landscape.

**Responses**

- `200` — OK
  - `application/json`: array of [Variant](../schemas/Variant.md)

### GET `/landscape/variants/{variantId}`

Retrieve a variant by its UUID.

**Parameters**

- `variantId` (path, required, string (uuid))

**Responses**

- `200` — OK
  - `application/json`: [Variant](../schemas/Variant.md)
- `404` — Not Found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

