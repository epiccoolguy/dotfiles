# autonix

Automatically set up a system using Nix.

1. `sh <(curl -L https://nixos.org/nix/install)`
2. `nix-shell -p git --run 'git clone https://github.com/epiccoolguy/autonix ~/.config/nix'`
3. `nix run --extra-experimental-features flakes nix-darwin -- switch --flake ~/.config/nix`
4. `switch`
