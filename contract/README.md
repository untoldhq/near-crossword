Crossword Smart Contract
==================

A [smart contract] written in [Rust] that demonstrates a crossword puzzle on the NEAR blockchain.


Quick Start
===========

Before you compile this code, you will need to install Rust with [correct target]


Exploring The Code
==================

1. The main smart contract code lives in `src/lib.rs`. You can compile it with
   the `./build.sh` script.
2. Tests: You can run smart contract tests with the `./test.sh` script. This runs
   standard Rust tests using [cargo] with a `--nocapture` flag so that you
   can see any debug info you print to the console.


  [smart contract]: https://docs.near.org/docs/develop/contracts/overview
  [Rust]: https://www.rust-lang.org/
  [correct target]: https://github.com/near/near-sdk-rs#pre-requisites
  [cargo]: https://doc.rust-lang.org/book/ch01-03-hello-cargo.html
