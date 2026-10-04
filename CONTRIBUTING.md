# Contribute to the documentation

Create a branch, edit the relevant MDX pages and navigation, and open a pull request. Check the implementation in [whatsapp-rust](https://github.com/oxidezap/whatsapp-rust), including public reexports, feature gates, errors, and tests. Link the audited source revision and relevant merged PRs in your description.

Document the current contract. Remove obsolete methods and examples instead of appending migration history. Keep contract details in the API reference and show practical use in guides. Update Portuguese getting-started pages when their examples change.

Use active voice, second person, concise sentences, and sentence-case headings. Preserve distinctions between content IDs, operation IDs, server IDs, partial successes, and durable completion. Construct extensible DTOs with their supported constructors, defaults, setters, or builders.

Run `mint dev`, `mint broken-links`, and `mint validate`. Compile complete Rust examples against the audited source revision with the relevant features. State any unavailable checks in the PR; do not report unexecuted checks as passing.
