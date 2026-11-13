# Amogh Ramesh

I work on data platforms at Texas Instruments in Bengaluru. Outside work, I contribute to Apache DataFusion and build projects in C++, Rust and Go.

I started learning Rust because I wanted to contribute to DataFusion. That has taken me into its foreign-function interface, query optimiser and SQL behaviour.

[Portfolio](https://www.ramogh.com) · [LinkedIn](https://www.linkedin.com/in/ramogh2404/) · [Email](mailto:ramogh2404@gmail.com)

## Open source

**Apache DataFusion · Rust**

Selected merged changes:

- [Keep writable tables writable across FFI](https://github.com/apache/datafusion/pull/23906): preserve table-provider delete, update and truncate overrides, with tests through a dynamically loaded library.
- [Fix arithmetic negation in the optimiser](https://github.com/apache/datafusion/pull/24668): remove bitwise-complement rewrites that produced incorrect results for unary minus.
- [Preserve aggregate null-handling support](https://github.com/apache/datafusion/pull/23908): carry the capability across the FFI boundary, with positive and negative regression cases.

[All merged DataFusion contributions →](https://github.com/apache/datafusion/pulls?q=is%3Apr+author%3AAmogh-2404+is%3Amerged)

**dbt-spark · Python**

[Three-part identifiers — PR #2140](https://github.com/dbt-labs/dbt-adapters/pull/2140) is open for review. It adds catalog-qualified relation names across discovery, caching, incremental models and snapshots, with Spark/Iceberg compatibility tests.

## Projects

| Project | What I worked on |
| :--- | :--- |
| **[Tez](https://github.com/Amogh-2404/Tez)** · C++17 | A compact HTTP server using Boost.Asio and Beast. Per-connection ownership, ordered pipelining, bounded requests and socket-level protocol tests. [Design notes](https://github.com/Amogh-2404/Tez/blob/main/docs/architecture.md). |
| **[MiniLang](https://github.com/Amogh-2404/minilang)** · C++ / LLVM 18 | A teaching compiler based on LLVM Kaleidoscope, with my own constant-folding, dead-code elimination and loop-invariant code motion passes. FileCheck tests inspect the transformed IR. |
| **[Split-ordered lists](https://www.ramogh.com/work/split-ordered-lists)** · Go | A guided study of concurrent hash tables: lazy bucket initialisation, compare-and-swap and two-phase deletion. The link is a public write-up; the source is private. |

## What I want to work on next

Database engines, storage and the infrastructure around them. I enjoy work where understanding the behaviour means reading the implementation and writing a test that makes the problem visible.

If your team works in this area, you can reach me at **[ramogh2404@gmail.com](mailto:ramogh2404@gmail.com)**.
