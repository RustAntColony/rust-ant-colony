# Ant Colony Simulation
This is an ant colony simulation, it internally uses kdtree and query caching, it's able to handle about 20k+ ants on the cpu.


Built with [Rust](https://www.rust-lang.org/) and [Bevy](https://bevyengine.org/) game engine

Follow us on X (https://x.com/rustantcolony)

# Usage
- Create your own ant simluation by adding food deposits, colony banks, crypto usage, and more.

- Run the simulation
```bash
cargo run --release
```

## Configurations
- The project config file is located at `src/configs.rs`
- If all ants aren't forming a single trail even after a long time, try increasing `ANT_INITIAL_PH_STRENGTH` in the configs to a greater value (exmaple: `40.0`)
