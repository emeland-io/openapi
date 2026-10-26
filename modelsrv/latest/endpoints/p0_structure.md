# p0_structure

endpoints for elements of the model pertaining to phase 0 of the EmELand model concerning contexts.

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

