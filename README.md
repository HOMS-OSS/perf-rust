# perf-rust

Timothy Maloney, Briana Oursler, Greg Hairfield, Sam Little, Michael Scherrer

Perf-rust is a Rust adaptation of the [linux perf command][1], also called perf_events.

## Goals

Our goal is to create a fast, reliable translation of `perf` in the Rust language with a least a couple software events implemented.


## RoadMap

*Minumum Viable Product* (MVP)

Hardware events
- cpu-cycles
- instructions 
- L1-dcache-loads

Software events
- context switches
- cpu-clock
- task-clock



## Requirements

Rust is required for this project.

For macOS, Linux, or other Unix-like OS, it is recommended to download Rustup and install Rust.

In terminal type:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

More information about installing Rust [here][3].


## Contributing Guidelines

Perf rust is an open source project and is open to recieving contributions in the form of tutorials, blog posts, submitting bug reports and feature requests!

## Code of Conduct

 We are committed to providing a friendly, safe and welcoming environment for all, regardless of level of experience, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, religion, nationality, or other similar characteristic.

 See [Rust Community Code of Conduct][4]

## License
[Gplv2][2]








[1]:https://perf.wiki.kernel.org/index.php/Main_Page
[2]:https://choosealicense.com/licenses/gpl-2.0/
[3]:https://www.rust-lang.org/tools/install
[4]:https://www.rust-lang.org/policies/code-of-conduct