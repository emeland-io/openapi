# MetricValue

Current reading of a MetricInstance. The value field is the current value only, not a timeline.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md))
- `description` (string)
- `displayName` (string, required)
- `metricInstanceRef` ([MetricInstanceRef](./MetricInstanceRef.md), required) — Reference to a MetricInstance.
- `metricValueId` (string (uuid), required)
- `value` (string, required) — Current value of the metric (unvalidated string).

