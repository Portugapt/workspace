# Alacritty

## Install

[How to Install](https://github.com/alacritty/alacritty/blob/master/INSTALL.md)

Assuming you have [Cargo installed](./cargo.md)

```bash
git clone https://github.com/alacritty/alacritty.git
cd alacritty
```

### Ubuntu

Dependencies:

```bash
apt install cmake pkg-config libfreetype6-dev libfontconfig1-dev libxcb-xfixes0-dev libxkbcommon-dev python3
```

Build:

```bash
cargo build --release
```