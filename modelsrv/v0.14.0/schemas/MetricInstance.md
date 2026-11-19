# MetricInstance

A concrete instantiation of a Metric bound to an optional subject (the resource the metric is measured for). MetricInstances are not time series; they name the measured thing, while MetricValue carries the current reading.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md))
- `description` (string)
- `displayName` (string, required)
- `metricInstanceId` (string (uuid), required)
- `metricRef` ([MetricRef](./MetricRef.md)) — Reference to a Metric vocabulary entry.
- `subject` ([ResourceRef](./ResourceRef.md))

