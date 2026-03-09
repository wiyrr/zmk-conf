# zmk-conf

## Flashing with nix-zmk

1. Run `udiskie` daemon for automount (optional)

```sh
udiskie &
```

1. Run `nix run .#flash` to flash firmware

```sh
cd ./path_to_this_repository
Run nix run .#flash to flash firmware
