# Using nix flakes to create dev shells

## Dependencies
`direnv` needs to be installed.

## Setup
1. Install any packages you want inside flake.nix.

2. `direnv allow .`

3. `echo "use flake ." > .envrc`
