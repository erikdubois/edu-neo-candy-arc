# edu-neo-candy-arc

A neo Candy icon theme variant built on the Arc design language. Part of Erik's `~/EDU/` Neo-Candy family — sweet, colourful icons that play well with Arc-derived GTK themes.

## What's in this repo

- `usr/share/icons/` — the icon theme assets that land in `/usr/share/icons/`.
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Sibling variants

- [edu-neo-candy-arc-mint-grey](https://github.com/erikdubois/edu-neo-candy-arc-mint-grey)
- [edu-neo-candy-arc-mint-red](https://github.com/erikdubois/edu-neo-candy-arc-mint-red)
- [edu-neo-candy-qogir](https://github.com/erikdubois/edu-neo-candy-qogir)
- [edu-neo-candy-tela](https://github.com/erikdubois/edu-neo-candy-tela)

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-neo-candy-arc
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-neo-candy-arc.git
cd edu-neo-candy-arc
sudo cp -r usr/share/icons/. /usr/share/icons/
sudo gtk-update-icon-cache -f /usr/share/icons/<theme-folder>
```

### Activate

```bash
gsettings set org.gnome.desktop.interface icon-theme "<theme-folder-name>"
```

Or set via your DE's appearance settings.

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

## License

See [LICENSE](./LICENSE).
