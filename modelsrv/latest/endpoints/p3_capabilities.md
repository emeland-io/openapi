# p3_capabilities

endpoints for elements of the model pertaining to phase 3 of the EmELand model concerning offered capabilities and orders to consume these capabilities.

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

