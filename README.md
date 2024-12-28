# Archetect Render Github Action

This Github Action unleashes the full power of Archetect within a Github Workflow.

Basic Usage:

```yaml

- uses: archetect/render-action@v1
  with:
    source: "https://github.com/archetect-rust/rust-service-tonic-grpc.archetype.git"
    args: "-a project-prefix=Example -a project-suffix=Suffix"

```
