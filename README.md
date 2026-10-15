# rpi-loader has moved

The loader, its host CLI and `rpi-loader-ota` are now developed in the
[rpi-hal repository](https://github.com/joeferner/rpi-hal/tree/main/loader),
together with rpi-hal, rpi-hal-embassy and rpi-kickstart.

- **Nothing changes for users.** The CLI is still
  [`rpi-loader` on crates.io](https://crates.io/crates/rpi-loader)
  (`cargo install rpi-loader`), and the library is still
  [`rpi-loader-ota`](https://crates.io/crates/rpi-loader-ota).
- **Loader images:** releases up to v0.5.0, with their images, remain on
  [this repository's release page](https://github.com/joeferner/rpi-loader/releases).
  New releases are tagged `loader-v<version>` (the CLI and images) and
  `loader-ota-v<version>` (the library) on
  [rpi-hal's release page](https://github.com/joeferner/rpi-hal/releases).
- **Issues** moved there, with the `loader` label. Old issue links
  redirect.
- **Pull requests** stay here.
- **Documentation:** the
  [loader's README](https://github.com/joeferner/rpi-hal/tree/main/loader)
  and [docs.rs/rpi-loader-ota](https://docs.rs/rpi-loader-ota).

This repository is archived and read-only.
