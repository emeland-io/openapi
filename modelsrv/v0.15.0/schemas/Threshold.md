# Threshold

Condition of arbitrary complexity attached to a MetricInstance. The condition itself lives in annotations (emeland.io/threshold.expression), not as schema fields.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md))
- `description` (string)
- `displayName` (string, required)
- `metricInstanceRef` ([MetricInstanceRef](./MetricInstanceRef.md), required) — Reference to a MetricInstance.
- `thresholdId` (string (uuid), required)

