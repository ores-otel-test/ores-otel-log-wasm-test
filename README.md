# ores-otel-log-wasm-test

Exact-head conformance harness for **wasm**.

This repository tests both `ores-otel/ores.otel.log` and `ORESoftware/next-loggers.ts` using explicit commit SHAs.
The required native command is recorded in `conformance.json`: `cargo test && wasm-tools validate target/wasm32-wasip2/release/*.wasm`.
