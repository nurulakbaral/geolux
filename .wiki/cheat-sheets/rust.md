# Rust

## Rust Workspace


### Root Config

```toml
[workspace]
members = ["<folder_name>/<package_name>", "crates/*"]
resolver = "2"
```

### Create Packages

- **Binary Package**: `cd <appa_name> && cargo new <app_name>`
- **Library Package**: `cd <appa_name> && cargo new <lib_name> --lib`

### Add Dependencies

```toml
[dependencies]
<lib_name> = { path = "../../crates/<lib_name>" }
```
