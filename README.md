# rpico-embasy-blinky-rs

 - You need the `nightly` rust compiler. With the rustup tool you can switch to
  that version like this:

```bash
rustup default nightly
```

 - You need the M0 - M1 arm cortex compiler:

 ```bash
rustup target add thumbv6m-none-eabi
 ```

 - For download the code to the raspberry-pico you need the `elf2uf2-rs` tool

```bash
cargo install elf2uf2-rs
```

NOTE: For download the code to the raspberry-pico hold the `BOOTSEL` button
later plug the usb port to the computer and you can see the `RPI-RP2` volumen in
your file mannager(you need that volume mounted). Later simply do:

```bash
cargo r --release
```

