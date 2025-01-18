<h3 align="center">
  <img src="https://raw.githubusercontent.com/qxb3/fum/refs/heads/main/repo/logo.png" width="200"/>
</h3>

<h2 align="center">
  fum: A fully ricable tui-based music client.
</h2>

<p align="center">
  fum is a tui-based mpris music client designed to provide a simple and efficient way to display and control your music within a tui interface.
</p>

<p align="center">
  <a href="https://github.com/qxb3/fum/pulls">
    <img src="https://img.shields.io/badge/OPEN-DEFEDF?style=for-the-badge&logo=github&label=Contributions&labelColor=1C1B22" />
  </a>

  <a href="https://github.com/qxb3/fum/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/MIT-DEFEDF?style=for-the-badge&logo=Pinboard&label=License&labelColor=1C1B22" />
  </a>

  <a href="https://github.com/qxb3/fum/stargazers">
    <img src="https://img.shields.io/github/stars/qxb3/fum?style=for-the-badge&logo=Apache%20Spark&logoColor=ffffff&labelColor=1C1B22&color=DEFEDF" />
  </a>

  <a href="https://aur.archlinux.org/packages/fum">
    <img src="https://img.shields.io/aur/version/fum?style=for-the-badge&logo=archlinux&logoColor=ffffff&labelColor=1C1B22&color=DEFEDF" />
  </a>

  <a href="https://crates.io/crates/fum-player">
    <img src="https://img.shields.io/crates/v/fum-player?style=for-the-badge&logo=rust&logoColor=ffffff&labelColor=1C1B22&color=DEFEDF" />
  </a>
</p>

## Demo

<img
  width="800px"
  src="https://github.com/user-attachments/assets/930283d8-6299-4ef9-865b-26960dcee866"
/>

## Installation

### Arch

```bash
yay -S fum
# paru -S fum
```

### Cargo (From Source)

> [!CAUTION]
> Installing from source is typically not recommended as it will probably have breaking stuff.

```bash
git clone https://github.com/qxb3/fum.git
cd fum
cargo build --release

# Either copy/move `target/release/yum` to /usr/bin
# Or add the release path to your system's path

# Moving fum binary to /usr/bin
mv target/release/fum /usr/bin
```

### Configuring

See [Wiki](https://github.com/qxb3/fum/wiki/Configuring)

## Showcase on a rice

<img src="https://github.com/qxb3/fum/blob/main/repo/showcase.png" />

## Contributing

Thank you for considering contributing to fum! Contributions are welcome and appreciated.

## LICENSE

[MIT](https://github.com/qxb3/fum/blob/main/LICENSE)
