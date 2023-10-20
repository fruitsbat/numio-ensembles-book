# Building the docs

The docs are written in [mdBook](https://github.com/rust-lang/mdBook). Check [their docs](https://rust-lang.github.io/mdBook/index.html) if you want to edit them.
A `flake.nix` and justfile are provided in the [git repo](https://github.com/fruitsbat/numio-ensembles-book).
If you have [nix](https://nixos.org/download) with [flakes](https://nixos.wiki/wiki/Flakes) set up you can edit the docs by running `nix develop`.
This will make all dependencies available as long as you are in the shell it creates.
You can run `just -l` to find all relevant commands for development.