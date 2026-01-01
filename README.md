## West setup

```shell
west init -l config
west update
west zephyr-export 
```

Build the profile

```shell
west  build  -p -s zmk/app -b nice_nano  -- -DSHIELD=lily58_left -DZMK_CONFIG=/full/path/zmk-for-keyboards/config
```
