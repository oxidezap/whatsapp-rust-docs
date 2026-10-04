# Documentation project instructions

This repository documents the current oxidezap/whatsapp-rust API using Mintlify. Content is MDX with YAML frontmatter; navigation is in `docs.json`.

- Audit merged source PRs, dates, public reexports, implementation, and tests before changing contracts.
- Document current behavior. Remove stale APIs and claims; do not add changelogs or versioned reference pages.
- Update affected reference pages, guides, and Portuguese getting-started examples together.
- Use active voice, second person, concise sentences, and sentence-case headings.
- Use supported constructors and builders for extensible DTOs. Keep content, operation, and server IDs distinct.
- Compile complete examples against the source revision recorded in the PR. Check feature-gated examples with their features.
- Run `mint dev`, `mint broken-links`, and `mint validate`; report unavailable checks accurately.
- Put source audit links and validation evidence in the PR description.
