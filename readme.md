# Using nix flakes to create dev shells

## Dependencies
- You should at least know the basics of [nix](https://nixos.org/) and [nix flakes](https://nixos.wiki/wiki/Flakes).
- Requires [direnv](https://direnv.net/).

## Setup
1. Install any packages you want inside flake.nix.

2. `echo "use flake ." > .envrc`

3. Run `direnv allow .`.
