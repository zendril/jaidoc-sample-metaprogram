# jaidoc-sample-metaprogram

This is a sample metaprogram that uses the jaidoc library to generate documentation for a sample module.

## Setup

Make sure you have initialized the submodules:

```sh
git submodule update --init --recursive
```

Or clone this repo with submodules:

```sh
git clone --recurse-submodules <repository-url>
```

## Usage

```sh
jai build.jai - clean build
```

This will generate documentation in the `target/docs` directory.