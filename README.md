## To build
cd ~/projects/zmk/app

```sh
west build -b nice_nano_v2 -- -DSHIELD=reviung41 -DZMK_CONFIG="/home/timwalker/projects/zmk-config/config"
# or clean build with --pristine
west build -b nice_nano_v2 --pristine -- -DSHIELD=reviung41 -DZMK_CONFIG="/home/timwalker/projects/zmk-config/config"
```

## TODO
- [ ] Adjust WIN layer for pop os shortcuts
- [ ] Explore injecting strings in combos/layers with zmk
