---
name: "API docs sync"
on:
  push:
    - repo: "oxidezap/whatsapp-rust"
context:
  - repo: "oxidezap/whatsapp-rust"
automerge: false
---

Read the changed source and identify its exact commit and publication status before adapting task examples. Keep repository links canonical. Update the current API guide for changed ID/secret/store contracts; remove obsolete APIs and changelog/versioned pages. Open a reviewable PR without merging it. Preserve distinct projections, partial failures and durability boundaries.

Use the library's Rustdoc and pinned source for exact signatures; do not recreate exhaustive DTO or overload catalogs in MDX. Use merged main-branch contracts; pending library PRs do not define the current reference. Compile changed Rust examples against the cited revision, check MDX and internal links, and update all affected task pages together. Never describe unreleased main-branch APIs as a published crates.io version merely because Cargo.toml retains that version number.
