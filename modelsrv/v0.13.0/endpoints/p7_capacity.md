# p7_capacity

endpoints for elements of the model pertaining to phase 7 of the EmELand model concerning capacity planing and management.

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

