# rust_esp32_std_hello_world
Just a simple Hello world example using Rust and the STD lib for an ESP32.

## Rust install
https://esp-rs.github.io/book/installation/installation.html

## Generated with:
```
cargo generate --git https://github.com/esp-rs/esp-idf-template cargo
🤷   Project Name: hello_world_std
⚠️   Renaming project called `hello_world_std` to `hello-world-std`...
🔧   Destination: .../hello-world-std ...
🔧   project-name: hello-world-std ...
🔧   Generating template ...
✔ 🤷   STD support · true
✔ 🤷   MCU · esp32
✔ 🤷   ESP-IDF native build version (v4.3.2 = previous stable, v4.4 = stable, mainline = UNSTABLE) · v4.4
✔ 🤷   Configure project to use Dev Containers (VS Code, GitHub Codespaces and Gitpod)? (beware: Dev Containers not available for esp-idf v4.3.2) · false
[ 1/10]   Done: .cargo/config.toml                                                                                                                             [ 2/10]   Done: .cargo                                                                                                                                         [ 3/10]   Done: .gitignore                                                                                                                                     [ 4/10]   Done: .vscode                                                                                                                                        [ 5/10]   Done: Cargo.toml                                                                                                                                     [ 6/10]   Done: build.rs                                                                                                                                       [ 7/10]   Done: rust-toolchain.toml                                                                                                                            [ 8/10]   Done: sdkconfig.defaults                                                                                                                             [ 9/10]   Done: src/main.rs                                                                                                                                    [10/10]   Done: src                                                                                                                                            🔧   Moving generated files into: `.../hello-world-std`...
💡   Initializing a fresh Git repository
✨   Done! New project created .../hello-world-std
```

## Run with:
```
. ~/export-esp.sh
. ~/$IDF-PATH/esp-idf/export.sh
cargo run --release
```
