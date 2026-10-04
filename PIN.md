# phase.rs v0.95.0, pinned for Stackheim

Upstream: https://github.com/phase-rs/phase at `v0.95.0` (`c3a337e764c4481907e0c362932f2b87793feb66`).
License: MIT OR Apache-2.0 (LICENSE-MIT, LICENSE-APACHE, NOTICE).

Only `crates/engine` and `crates/phase-ai` are kept, without `tests/` or
`phase-ai/fixtures/`. The root `Cargo.toml` drops the nightly-only
`codegen-backend` cargo feature and profile keys, and lists only those two
members. Nothing else is changed.

Built by `docs/research/referee-host-probe/make-pin.sh` in pxheim/stackheim.
