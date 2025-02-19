# copyup

A command line tool for fetching licenses

------------------- 
## Installation


### From Source
```sh
git clone https://github.com/swarley/copyup
cd copyup
cargo install --path .
```

### Via `cargo install`
```sh
cargo install copyup
```

### Precompiled package or binary

Obtain the file relevant to you from [releases](https://github.com/swarley/copyup/releases)

-------------------


## Usage

```sh
# download the MIT license to `LICENSE'
copyup mit

# output to stdout
copyup gpl-3.0 -s

# specify output path
copyup mit -o MIT.license

# view a list of all available licenses
copyup -l
```

Licenses names are all based on SPDX identifiers and are not case sensitive.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/swarley/copyup.

## License

The app is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
