# PCManFM configuration

Ansichts-, Fenster- und Bedienungseinstellungen für den grafischen Dateimanager.

**[Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/components/#pcmanfm)** ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- pcmanfm
```

Paket: `arch-dotfiles-pcmanfm`. Datei: `~/.config/pcmanfm/default/pcmanfm.conf`.
LibFM- und GTK3-Konfigurationen werden als Abhängigkeiten installiert.
Quellen hier bearbeiten, committen und auf `main` pushen; nach erfolgreichem
Registry-Build mit `sudo pacman -Syu` aktualisieren. [PACKAGING.md](PACKAGING.md).

### Anpassung

`~/.config/pcmanfm/default/pcmanfm.conf` steuert das Benutzerprofil. LibFM und GTK3 haben getrennte Konfigurationsdateien. Änderungen nach einem Neustart von PCManFM prüfen.

Eigene Änderungen in der aktivierten Benutzerkopie bleiben bei der Synchronisierung erhalten; neue abweichende Vorgaben erscheinen als `.pacnew`. Siehe [Update und Wiederherstellung](https://arch-dotfiles.readthedocs.io/en/latest/verification/).

[![Package safety](https://github.com/MichaelWeissDEV/pcmanfm-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/pcmanfm-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
