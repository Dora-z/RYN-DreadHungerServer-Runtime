# RYN Dread Hunger Server Runtime

This repository publishes verified runtime assets for the RYN Dread Hunger Server launcher.

Runtime executables are distributed only as GitHub Release assets. They are not committed to Git history. The Electron launcher downloads the selected asset through the configured GitHub acceleration endpoint, verifies the compressed asset SHA-256, decompresses it locally, and verifies the executable SHA-256 before launch.

Current release:

- Tag: `runtime-0.2.47`
- Asset: `DreadHungerServer-rust-0.2.47.exe.br`
- Compression: Brotli
- Platform: Windows x64

This repository does not contain Dread Hunger game or dedicated-server binaries.
