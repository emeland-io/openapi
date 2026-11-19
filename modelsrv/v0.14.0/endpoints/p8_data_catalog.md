# p8_data_catalog

endpoints for elements of the model pertaining to phase 8 of the EmELand model concerning a data catalog.

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

