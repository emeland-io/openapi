# MergeRule

Documents a merge rule registered in a modelsrv instance. Merge rules describe how change events may be merged into existing resources.

- **Type:** object

## Properties

- `description` (string) — A brief description of what the merge rule does.
- `displayName` (string, required) — The human-readable name of the merge rule.
- `ruleId` (string (uuid), required) — An UUID that uniquely identifies the merge rule.

