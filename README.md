# Sensirion SGPC3 driver
Embedded hal based Rust Sensirion Sgpc3 driver

[![Build status][workflow-badge]][workflow]
[![Crates.io Version][crates-io-badge]][crates-io]
[![Crates.io Downloads][crates-io-download-badge]][crates-io-download]
![No Std][no-std-badge]

Platform agnostic Rust driver for Sensirion SGPC3 gas sensor using the [`embedded-hal`](https://github.com/japaric/embedded-hal) traits.

## Sensirion SGPC3

Sensirion SGPC is a low-power accurate gas sensor for air quality application. The sensor has different sampling rates to optimize power-consumption per application bases as well as ability save and set the baseline for faster start-up accuracy. The sensor uses I²C interface and measures TVOC (*Total Volatile Organic Compounds*)

Datasheet: https://www.sensirion.com/file/datasheet_sgpc3

## no_std

For use in 'no_std' environments, use the `no_std` feature. Add this to your `Cargo.toml`

    sgpc3 = {version = "0.0.4", features = ["no_std"]}


## Development status
The sensor is feature complete and the future development evolves:
- Moving into using Embedded-hal 1.x


## License

Licensed under either of

 * Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
   http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or
   http://opensource.org/licenses/MIT) at your option.


### Contributing

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.

<!-- Badges -->
[workflow]: https://github.com/mjaakkol/sgpc3-rs/actions?query=workflow%3ARust
[workflow-badge]: https://img.shields.io/github/workflow/status/mjaakkol/sgpc3-rs/Rust/master
[crates-io]: https://crates.io/crates/sgpc3
[crates-io-badge]: https://img.shields.io/crates/v/sgpc3.svg?maxAge=3600
[crates-io-download]: https://crates.io/crates/sgpc3
[crates-io-download-badge]: https://img.shields.io/crates/d/sgpc3.svg?maxAge=3600
[no-std-badge]: https://img.shields.io/badge/no__std-yes-blue
