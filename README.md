# LED flash cross

## What is this?

A sample program to flashing LEDs on Raspberry Pi.
It's able cross build.

## How does it work?

### Dependencies

- [rppal](https://github.com/golemparts/rppal)
- [cross](https://github.com/cross-rs/cross) (for cross building)

### Usages

```bash
# In Raspberry Pi
cargo run --release

# In other environments (need cross build)
cross build --target aarch64-unknown-linux-gnu --release
```
