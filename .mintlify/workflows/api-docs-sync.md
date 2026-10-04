---
name: "API docs sync"
on:
  push:
    - repo: "oxidezap/whatsapp-rust"
context:
  - repo: "oxidezap/whatsapp-rust"
automerge: true
---

Read the changed source and identify its exact commit and publication status before adapting task examples. Keep repository links canonical. Update the current API migration guide for removals and changed ID/secret/store contracts. Preserve distinct projections, partial failures and durability boundaries.

Use the library's Rustdoc and pinned source for exact signatures; do not recreate exhaustive DTO or overload catalogs in MDX. Compile changed Rust examples against the cited revision, check MDX and internal links, and update all affected task pages together. Never describe unreleased main-branch APIs as a published crates.io version merely because Cargo.toml retains that version number.

## Maintain one reference

Put new public construction and host-trait proofs in the existing consolidated consumer, not another crate. Consumer task examples belong here; exact signatures and low-level invariants belong in source Rustdoc. When changing the source pin, compile the examples against that revision and verify native, published MSRV and WASM feature profiles before updating claims.
