# Substrate Off-chain Worker Demo

This repository is built based on [Substrate Node Template `v3.0.0+monthly-2021-10`](https://github.com/substrate-developer-hub/substrate-node-template/tree/v3.0.0+monthly-2021-10).

The purpose is to demonstrate what off-chain worker could do, and how one would go about using it.

### Run

1. First, complete the [basic Rust setup instructions](./docs/rust-setup.md).

2. To run it, use Rust's native `cargo` command to build and launch the template node:

  ```sh
  cargo run --release -- --dev --tmp
  ```

3. To build it, the `cargo run` command will perform an initial build. Use the following command to
build the node without launching it:

  ```sh
  cargo build --release
  ```

Since this repository is based on Substrate Node Template,
[it's README](https://github.com/substrate-developer-hub/substrate-node-template/blob/v3.0.0%2Bmonthly-2021-10/README.md)
applies to this repository as well.

### More about Off-chain Worker

- Goto [here](docs/ocw-index.md) to learn more about off-chain worker (extracted from Substrate
Recipes, based on Substrate v3).

- Review the code of [**Offchain Worker Example Pallet** within Substrate](https://paritytech.github.io/substrate/latest/src/pallet_example_offchain_worker/lib.rs.html#18-709)
and its [rustdoc](https://paritytech.github.io/substrate/latest/pallet_example_offchain_worker/). This pallet is also [added in this repository](pallets/example-offchain-worker).
