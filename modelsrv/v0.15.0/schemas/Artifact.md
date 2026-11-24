# Artifact

Represents a binary artefact (e.g. software package, archive, binary executable) tracked in the landscape.

- **Type:** object

## Properties

- `annotations` (array of [Annotation](./Annotation.md)) — A set of key-value pairs for storing additional metadata about the artifact.
- `artifactId` (string (uuid), required) — UUID that uniquely identifies the artifact.
- `description` (string) — A description of the artifact.
- `displayName` (string, required) — A human-readable name of the artifact.
- `hash` (string) — Hash of the binary object in the format algorithm:hex (e.g. "SHA256:9e9b...").

