# Halloy

___IRC client written in Rust___

Halloy is an open-source IRC client written in Rust, with the Iced GUI library. It aims to provide a simple and fast client for Mac, Windows, and Linux platforms. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub org.squidowl.halloy
flatpak run org.squidowl.halloy
```

## Building

```bash
git clone git@github.com:flathub/org.squidowl.halloy.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.squidowl.halloy.json
```

---

**Technologies**: Freedesktop, Iced, Rust
