# smudge-zmk

### Setup & Build
1. Complete [development setup](https://zmk.dev/docs/development/setup)
2. Place content of repo in `app/boards/shields/smudge`
3. Build with `cd app && west build -b seeeduino_xiao_ble -- -DSHIELD=smudge_right` (or `smudge_left`)

### Useful links
- [ZMK Behaviors](https://zmk.dev/docs/behaviors/key-press)
- [ZMK Keycodes](https://zmk.dev/docs/codes)
