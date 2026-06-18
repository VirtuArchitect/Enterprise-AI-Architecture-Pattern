# Contributing

EAAP documents are governance artifacts, so changes should be deliberate, traceable, and register-aligned.

## Document Changes

- Update [docs/index.md](docs/index.md) when adding, removing, renaming, or changing the status of a document.
- Keep [docs/governing-rules.md](docs/governing-rules.md) aligned with framework documents.
- Keep [docs/decision-model.md](docs/decision-model.md) aligned with architecture documents.
- Add generated PDFs only after exporting from sanitized DOCX sources and rerunning repository hygiene checks.
- Do not add third-party reference PDFs unless their licence permits redistribution and the licence is documented.

## Hygiene Rules

The repository intentionally avoids:

- unpublished company or product names;
- private/confidential packaging labels in public framework documents;
- em dashes, en dashes, nonbreaking hyphens, Unicode hyphens, and Unicode minus signs.

The GitHub Actions workflow in `.github/workflows/repository-hygiene.yml` enforces these checks on push and pull request.

## Implementation Material

Files under [implementation/](implementation/) are public interface examples, not a production reference implementation. Avoid adding runnable production claims unless the implementation includes installation, threat model, security controls, tests, and operational limitations.
