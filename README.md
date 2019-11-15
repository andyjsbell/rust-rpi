# rust-rpi

Looking at cross compiling Rust on RPi3.  Useful page is https://forge.rust-lang.org/release/platform-support.html


```$ sudo apt-get install -qq gcc-arm-linux-gnueabihf```

```$ rustup target add armv7-unknown-linux-gnueabihf```

```$ cargo build --target=armv7-unknown-linux-gnueabihf```