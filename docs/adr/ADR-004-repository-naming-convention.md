# ADR-004: Repository Naming Convention

- Status: Accepted
- Date: 2026-09-20
- Decision Maker: Rafael Martín Rodríguez

## Context

EngineRoom is intended to become a long-term engineering knowledge repository covering multiple technologies and learning paths.

As the repository grows, inconsistent naming conventions would reduce readability, complicate navigation and increase maintenance effort.

A single repository-wide naming convention is therefore required.

---

## Decision

The repository adopts the following naming conventions.

### Language

All directory names, file names and documentation are written in English.

---

### Case Style

Directory and file names use **kebab-case**.

Examples:

```text
machine-learning
prompt-engineering
control-flow
```

---

### Ordered Learning Paths

Whenever content represents a sequential learning path, directory names begin with a two-digit numeric prefix.

Examples:

```text
01-programming
02-databases
03-devops
```

Within a technology:

```text
01-fundamentals
02-intermediate
03-advanced
04-projects
```

Within a learning module:

```text
01-variables
02-data-types
03-operators
04-control-flow
```

---

### Internal Structure

Each learning module follows a common structure.

Example:

```text
01-variables/

README.md

01-theory/
02-examples/
03-exercises/
04-solutions/
05-quiz/
06-references/
```

---

### Markdown Files

Sequential Markdown files also use numeric prefixes.

Example:

```text
01-introduction.md
02-variable-definition.md
03-variable-assignment.md
04-best-practices.md
```

---

## Consequences

### Positive

- Consistent repository organization.
- Predictable navigation.
- Clear learning sequence.
- Easier maintenance.
- Better scalability.

### Negative

- Occasional renumbering may be required when inserting new learning modules.
- Contributors must follow the established naming convention.

## Alternatives Considered

### Unnumbered directories

This approach was rejected because EngineRoom is designed as a structured learning path rather than a simple collection of notes.
