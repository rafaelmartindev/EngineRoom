# ADR-002: Repository Structure

- Status: Accepted
- Date: 2026-09-19
- Decision Maker: Rafael Martín Rodríguez

## Context

EngineRoom is expected to grow continuously, incorporating new technologies, engineering disciplines and practical projects.

Without a consistent organizational structure, the repository could become difficult to navigate, maintain and extend.

A predictable layout improves scalability, discoverability and long-term maintainability.

## Decision

The repository will be organized into independent learning domains.

Each top-level module will represent a specific engineering discipline or technology.

Examples include:

- Programming
- Databases
- DevOps
- Cloud
- Artificial Intelligence
- Software Architecture

Each module will contain its own documentation, examples, exercises and projects whenever appropriate.

Repository-wide documentation will remain outside individual modules.

## Consequences

### Positive

- Consistent repository organization.
- Easier navigation.
- Independent evolution of modules.
- Better scalability.
- Reduced duplication of documentation.

### Negative

- Requires discipline when creating new modules.
- Some modules may require restructuring as the repository evolves.

### Alternatives Considered

**Single flat structure**

Keeping every technology at the repository root was considered.

This approach was rejected because it scales poorly as the number of technologies increases and makes navigation more difficult.
