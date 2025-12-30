# lumen-prism

[![CI](https://github.com/Tranduy1dol/lumen-prism/actions/workflows/ci.yml/badge.svg)](https://github.com/Tranduy1dol/lumen-prism/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/Tranduy1dol/lumen-prism/graph/badge.svg)](https://codecov.io/gh/Tranduy1dol/lumen-prism)

> ✨ Part of the [luminescent](https://github.com/Tranduy1dol/luminescent) project — *Illuminating the path to zero-knowledge*

A secure Multi-Party Computation (MPC) framework combining cryptographic primitives for distributed trust.

> ⚠️ **Educational Purpose Only**: This library is for learning purposes and is **NOT production-ready**.

## Features (Planned)

- High-performance networking
- Lattice-based commitment schemes for post-quantum security
- Zero-Knowledge Proofs for verifiable computation
- Threshold cryptography for distributed trust

## Installation

Add the following to your `Cargo.toml`:

```toml
[dependencies]
lumen-prism = { git = "https://github.com/Tranduy1dol/lumen-prism" }
```

## Usage

```rust
use lumen_prism::*;

fn main() {
    // Your code here
}
```

## Development

```bash
# Run tests
cargo test

# Run benchmarks
cargo bench

# Format code
cargo fmt

# Run clippy
cargo clippy
```

## Related Projects

This library is part of the [luminescent](https://github.com/Tranduy1dol/luminescent) learning monorepo for Zero-Knowledge Proofs.

## License

This project is licensed under the MIT License.
