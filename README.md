# Tracy Rust Demo

Demonstrating client setup and client markup for [Tracy Profiler](https://github.com/wolfpld/tracy) in Rust using [rust_tracy_client](https://github.com/nagisa/rust_tracy_client). Find more details [here](https://www.abhirag.com/blog/tracy/).

## Disable Tracy

Tracy is enabled by default. To disable it, replace the line below in [Cargo.toml](Cargo.toml):
```
tracy-client = { version = "0.12.6", default-features = false, features = ["enable"] }
```
with:
```
tracy-client = { version = "0.12.6", default-features = false }
```