# linely

Fast line/byte counter written in Rust

## What it does

- Zero dependencies outside std
- Reads stdin or multiple files
- Counts lines, words and bytes like wc
- Parallel over files with std threads

## Installation

```bash
cargo build --release
```

## Usage

```bash
./target/release/linely src/*.rs
cat README.md | ./target/release/linely
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── Cargo.toml
├── LICENSE
└── SECURITY.md
```

## License

MIT. Do whatever you want.
