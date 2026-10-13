# qte-popups

Random game-style quick-time event popups for Linux Mint (GTK3 / Python).

## Build and install
```
./build.sh
sudo apt install ./qte-popups_1.0.0_all.deb
```

## Try it
```
qte-popups --now                                   # first popup in 2 seconds
qte-popups --min-interval 5 --max-interval 15      # fast testing
```

## Options
`--min-interval`, `--max-interval` (seconds), `--timeout`, `--mash-chance`, `--no-grab`, `--now`

Autostart options live in `/etc/xdg/autostart/qte-popups.desktop` (`Exec=` line).

## Layout
- `src/usr/bin/qte-popups` – the program
- `src/etc/xdg/autostart/` – autostart entry
- `src/usr/share/applications/` – app-menu test launcher
- `src/DEBIAN/control` – package metadata
