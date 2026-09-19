# ADR-003: Repository Language

- Status: Accepted
- Date: 2026-09-19
- Decision Maker: Rafael Martín Rodríguez

## Context

EngineRoom is intended to become a long-term engineering repository and a professional portfolio.

Software engineering is an international discipline where English is the de facto standard for documentation, source code, technical discussions and open-source collaboration.

Using multiple languages would reduce consistency and increase maintenance effort.

## Decision

English will be the primary language for all repository content.

This includes:

- Documentation
- ADRs
- READMEs
- Markdown files
- Source code comments
- Commit messages
- Issues
- Pull Requests
- Diagrams where practical

Exceptions may be made for documents explicitly intended for Spanish-speaking audiences, but they should remain outside the core repository whenever possible.

## Consequences

### Positive

- Consistent documentation.
- Improved accessibility for international developers.
- Better alignment with open-source practices.
- Stronger professional portfolio.

### Negative

- Requires additional effort when writing documentation.
- Occasional language review may be necessary.

### Alternatives Considered

**Bilingual documentation**

Maintaining both English and Spanish documentation was considered.

This approach was rejected because it duplicates maintenance effort and increases the risk of documentation becoming inconsistent.