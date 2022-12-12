# {{crate_name}}

[![Clippy](https://github.com/{{origin}}/{{crate_name}}/actions/workflows/clippy.yml/badge.svg)](https://github.com/{{origin}}/{{crate_name}}/actions/workflows/clippy.yml)
[![Rust](https://github.com/{{origin}}/{{crate_name}}/actions/workflows/rust.yml/badge.svg)](https://github.com/{{origin}}/{{crate_name}}/actions/workflows/rust.yml)

***

{{description}}

## Getting Started

### Building from the Source

Make sure you have rust installed on your host system

#### *Clone the repository*

```bash
git clone https://github.com/{{origin}}/{{crate_name}}
```

#### *Setup the environment*

```bash
cargo xtask setup
```

#### *Start the application*

```bash
cargo xtask start
```

### Docker

Make sure you have docker installed on the target system

#### *Pull the image*

```bash
docker pull {{origin}}/{{crate_name}}:latest
```

#### *Build the image locally (optional)*

```bash
docker buildx build --tag {{origin}}/{{crate_name}}:latest .
```

#### *Run the image*

```bash
docker run {{origin}}/{{crate_name}}:latest
```

## Usage

### Builder (xtask)

```bash
    cargo xtask -h 
```

## Contributors

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

- [Apache-2.0](https://choosealicense.com/licenses/apache-2.0/)
- [MIT](https://choosealicense.com/licenses/mit/)
