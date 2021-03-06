# androidx-release-watcher

Rust binary that polls Google's Maven repository and finds the latest version of the requested dependencies.

## Installation

### Using `cargo`

Run `cargo install adx` on a terminal.

### From source

```shell
git clone https://github.com/msfjarvis/androidx-release-watcher
cd androidx-release-watcher
cargo install --path .
```

## Usage

### Find latest release of a package

```shell
$ adx appcompat
androidx.appcompat:appcompat:1.3.0-alpha02
androidx.appcompat:appcompat-resources:1.3.0-alpha02
```

### Find latest stable version of a package

```shell
$ adx --channel stable appcompat
androidx.appcompat:appcompat:1.2.0
androidx.appcompat:appcompat-resources:1.2.0
```
