# ores-otel-log-wasm-test

Exact-head **wasm** conformance harness for `ores-otel/ores.otel.log` and `ORESoftware/next-loggers.ts`.

Native verification command: `cargo test && wasm-tools validate target/wasm32-wasip2/release/*.wasm`.

Promotion requires both sources to pass at explicit 40-character commit SHAs.
