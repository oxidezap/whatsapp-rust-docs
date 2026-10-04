# WhatsApp Rust documentation

Documentation for the current [oxidezap/whatsapp-rust](https://github.com/oxidezap/whatsapp-rust) API, built with Mintlify. Read it at https://whatsapp-rust.jlucaso.com.

Pages are MDX; `docs.json` defines navigation. English has the full reference and guides. Portuguese covers getting started.

## Local development

Install the CLI with `npm install -g mint`, then run these commands from this repository:

```sh
mint dev
mint broken-links
mint validate
```

## Updating the reference

Audit merged source PRs and implementation dates against the existing pages. Document current behavior, validate examples against the same source revision, and remove APIs or guarantees that no longer exist. Update all affected guides and language variants together. Put audit evidence in the pull request; this site has no changelog or versioned reference.

See [CONTRIBUTING.md](CONTRIBUTING.md) for review expectations.
