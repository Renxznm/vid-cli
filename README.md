# vid-cli 🎬

Watching YouTube on a browser is too heavy for my Celeron N4020, so I wrote this minimal Bash script as a workaround. 

A blazing fast, lightweight CLI YouTube player using `yt-dlp`, `fzf`, and `mpv`.

*Inspired by the amazing [ani-cli](https://github.com/pystardust/ani-cli).*

---

### 🎥 Demo
<video src="vid-cli-demo.mp4" width="100%" controls></video>

---

## 📦 Dependencies
- `yt-dlp` (Fetching links)
- `fzf` (Interactive UI)
- `mpv` (Video Player)
- `ffmpeg` (Merging 1080p video & audio)
- `gawk` (String parsing)

## 🚀 Installation

### 1. Arch Linux (AUR)
The easiest way to install on Arch-based distributions:
```bash
yay -S vid-cli-git
```

### 2. Manual Install (Git Clone)
For other distributions or manual installation:
```bash
git clone https://github.com/Renxznm/vid-cli.git
cd vid-cli
sudo cp vid-cli /usr/bin/vid-cli
sudo chmod +x /usr/bin/vid-cli
```
