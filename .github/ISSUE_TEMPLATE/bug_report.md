---
name: Bug report
about: A reproducible defect in a Vaelii repository
title: ''
labels: bug
assignees: ''
---

**What happened**
A clear description of the bug.

**Expected**
What you expected instead.

**Reproduce**
Steps to trigger it — ideally a self-contained REPL snippet starting from a fresh KB:

```clojure
(require '[vaelii.core :as v])
(def kb (v/open-kb {}))
;; minimal form that reproduces the problem
```

**Environment**
- Repository, and version / commit:
- Backend (if one is involved): <!-- memory | memory-dense | memory-columnar |
                                    disk | disk-memory | disk-dense |
                                    disk-columnar | overlay -->
- Reached through: <!-- library | lein cli | daemon | browser | a foreign-format reader -->
- JDK / OS:

**Output**
Any stack trace, and the `:type` on the `ex-info` if the engine refused something.
