## alfetch

 Alfetch - a CLI Bash script to show system information on Android devices in termux.

## Instalation

### Install

```sh 
curl -fSsl "https://raw.githubusercontent.com/luisadha/alfetch/main/alfetch" -o ~/.local/bin/alfetch && chmod +x ~/.local/bin/alfetch
```

### Uninstall

```sh
rm -f ~/.local/bin/alfetch && rm -rf ~/.config/alfetch
```

## Configuration

Location of the readable configuration place.

```sh
~/.config/alfetch/alfetch.config.conf
```

## Download latest config (Rekomendations)

```sh
curl -LO https://raw.githubusercontent.com/luisadha/alfetch/v0.0.5-lts/alfetch.config.conf
```