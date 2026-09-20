# twins

[![crates.io](https://img.shields.io/crates/v/twins.svg)](https://crates.io/crates/twins)
[![docs.rs](https://docs.rs/twins/badge.svg)](https://docs.rs/twins)

Digital-twin and simulation layer for the [userspace.party](https://userspace.party) ecosystem.

## Role

`twins` is reserved for models that connect computational representations to physical or simulated systems: state, observation, simulation, actuation, and eventually model-driven interaction with the material world.

The crate depends on the lower-level `ample` and `userspace` layers and is built as part of the same freestanding systems family.

## Current state

The crate is presently a minimal `no_std` scaffold with freestanding entry/startup support. Its public modeling API has not yet been established.

Earlier research links and exploratory material that lived in this README are not the crate API. The README now reflects the software that actually exists; research references can live separately as the modeling work develops.

## Use

```bash
cargo add twins
```

Consumers should currently treat the crate as experimental infrastructure rather than a stable digital-twin framework.

## Ecosystem

- Ecosystem: https://userspace.party
- Crate homepage: https://userspace.party/twins
- API documentation: https://docs.rs/twins
- crates.io: https://crates.io/crates/twins
- Source: https://github.com/ze-gois/rust_twins
- Workspace hub: https://github.com/ze-gois/rust_userspace_hub

## Status

Early experimental scaffold. The intended domain is clear; the Rust API is still to be designed.

## License

See [LICENSE](LICENSE).
