# ArtifactInstance

Represents a specific instance (copy/location) of an Artifact.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the artifact instance.
- `artifact` (string (uuid)) — UUID of the referenced Artifact.
- `artifactInstanceId` (string (uuid), required) — UUID that uniquely identifies the artifact instance.
- `description` (string) — A description of the artifact instance.
- `displayName` (string, required) — A human-readable name of the artifact instance.

