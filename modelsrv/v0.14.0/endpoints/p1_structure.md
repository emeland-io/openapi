# p1_structure

endpoints for elements of the model pertaining to phase 1 of the EmELand model concerning system structure, interfaces and system instances.

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

