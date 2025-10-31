### [Vesktop](https://github.com/Vencord/Vesktop)

# Install Vesktop

## 🧛‍♂️Debian/Ubuntu

1.  [Download `.deb`](https://github.com/Vencord/Vesktop/releases/download/v1.5.8/vesktop_1.5.8_amd64.deb)
2.  **Install via `apt` or `dpkg`:**
    ```bash
    cd ~/Downloads/
    sudo apt install ./vesktop-*.deb
    ```
    *   Alternative `sudo dpkg -i vesktop-*.deb` and then `sudo apt install -f` to fix any missing dependencies.

## 🧛‍♂️Fedora/RHEL/CentOS

1.  [Download x86 x64 `.rpm`](https://github.com/Vencord/Vesktop/releases/download/v1.5.8/vesktop-1.5.8.x86_64.rpm)<br>
1.2 [Download aarch64 `.rpm`](https://github.com/Vencord/Vesktop/releases/download/v1.5.8/vesktop-1.5.8.aarch64.rpm)
2.  **Install via `dnf`:**
    ```bash
    cd ~/Downloads/
    sudo dnf install ./vesktop-*.rpm
    ```
## 🧛‍♂️Arch Linux

1.  **Ensure `git` and `base-devel` are installed:**
    ```bash
    sudo pacman -S --needed git base-devel
    ```
2.  **Install Vesktop using the AUR helper:**
    ```bash
    yay -S vesktop
    ```
<br>

# Theme installation

#### Install using QuickCSS
Copy the contents in `Dracula.theme.css` raw file into Vesktop QuickCSS

### Copy Here ↓

### [`Dracula.theme.css`](https://raw.githubusercontent.com/CtorW/Vesktop-Discord/refs/heads/main/Dracula.theme.css)

#### Install using ThemeFolder

```bash
git clone https://github.com/CtorW/Vesktop-Discord.git ~/Dracord
cd ~/Dracord
sudo mv Dracula.theme.css ~/.config/vesktop/themes/
```

#### Activating theme

```ini
1. User settings
2. Themes
3. Activate the `Dracula Vesktop Theme`
```
