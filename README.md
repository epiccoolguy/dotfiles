# autonix

Automatically set up a system using Nix.

1. `sh <(curl -L https://nixos.org/nix/install)`
2. `source /etc/zshrc`
3. `nix-shell -p git --run 'git clone https://github.com/epiccoolguy/autonix ~/.config/nix'`
4. `nix run --extra-experimental-features nix-command --extra-experimental-features flakes nix-darwin -- switch --flake ~/.config/nix`
5. `source /etc/zshenv && source /etc/zprofile && source /etc/zshrc`
6. `switch`
