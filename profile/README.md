# <img src="logo.svg" alt="" width="26" height="26">&nbsp;Vaelii

**A contextualized common-sense knowledge base with a justified-inference reasoning engine.**

The unit of knowledge is a **sentex** — one sentence plus the one context it holds
in — stored over a flattened count-aware trie. Vaelii answers queries by fully
justified inference: forward and backward rule chaining, transitive closure, and
optional answer-set solving over assumption closures. It is symbolic and inspectable
rather than statistical, and uses no embeddings. Every answer traces the exact facts
and rules that entail it, and a truth-maintenance system keeps the knowledge base
consistent under retraction, removing any conclusion whose support is withdrawn.
Storage runs from in-memory to a durable on-disk store, and needs no external
service.

**Start with [vaelii](https://github.com/vaelii/vaelii)** — the engine boots and
tests on its own (`lein repl`), no database and no Docker. Its README is the front
door, and [`docs/`](https://github.com/vaelii/vaelii/tree/main/docs) is the full
manual: [`docs/index.md`](https://github.com/vaelii/vaelii/blob/main/docs/index.md)
maps every subsystem note, and
[`docs/glossary.md`](https://github.com/vaelii/vaelii/blob/main/docs/glossary.md)
defines the vocabulary. Longer-form writing lives at
[vaelii.com](https://vaelii.com).

## The repositories

| Repo | What it is |
|---|---|
| [vaelii](https://github.com/vaelii/vaelii) | The core engine — in-memory to on-disk out of the box, with a CLI, a headless daemon and a browser UI |
| [vaelii-foreign](https://github.com/vaelii/vaelii-foreign) | Foreign-format readers — OpenCyc, RDF/OWL, WordNet, OBO and ATOMIC, each translated into one corpus format |

## License

Copyright © 2026 Vaelii LLC and the Vaelii contributors. Licenses vary by
repository — always check the `LICENSE` in the one you're using:

- **Engine** ([vaelii](https://github.com/vaelii/vaelii)) — [SSPL-1.0](https://www.mongodb.com/licensing/server-side-public-license); source-available, not open source.
- **Foreign-format readers** ([vaelii-foreign](https://github.com/vaelii/vaelii-foreign)) — Apache-2.0.

Repositories published later carry their own terms; the knowledge-base data
(`vaelii-kb`, Q4 2026) will be CC BY. A converted corpus carries its *source's*
license, not the converter's.

Commercial licensing: **support@vaelii.com**.
