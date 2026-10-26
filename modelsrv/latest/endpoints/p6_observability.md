# p6_observability

endpoints for elements of the model pertaining to phase 6 of the EmELand model concerning observability, logging and monitoring.

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

