# ruhoh-google-data

Configurable [ruhoh][ruhoh] widget that defines structured data interpreted by Google.

[ruhoh]: https://github.com/ruhoh/ruhoh.rb

# Installation

```sh
git submodule add https://github.com/muroc/ruhoh-google-data widgets/google-data
```

# Configuration

Inside `config.yml`:

```yml
widgets :
  google_data:
    use: 'json-ld'
    name: 'SoftwarePhilosophy.Ninja'
    alternate: 'Software Philosophy' # Optional
    logo: 'http://muroc.github.io/softwarephilosophy.ninja/media/phi-logo.svg' # Optional
```

# Contribution

No rocket science here. If you need additional structured data, please add a config key and
conditional `ld+json` script.

Pull requests are welcome!

# License

Copyright &copy; 2016 Maciej Chałapuk. Released under [MIT license](LICENSE).

