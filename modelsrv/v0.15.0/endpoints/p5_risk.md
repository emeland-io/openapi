# p5_risk

endpoints for elements of the model pertaining to phase 5 of the EmELand model concerning managing risk and security.

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

