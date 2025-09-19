# adhan-cast
Play the Adhan on Google Home speakers at prayer times; web UI + scheduler, no Raspberry Pi.
# Adhan Cast (Google Home)
Play the Adhan on your Google Home speakers at prayer times from any device on your Wi-Fi.  
Includes a modern web UI, automatic daily scheduling, multiple Adhan tracks, and clean stop/fade.

![UI](docs/img/ui-1.png)

## ✨ Features
- Web UI (mobile-friendly) with **glass** design + custom wallpaper
- **Auto scheduler**: fetches prayer times daily (Aladhan API) and casts the Adhan automatically
- **Manual controls**: Play N seconds, Play Full, Stop
- **Multiple tracks**: choose `azan1.mp3 … azan5.mp3`
- **Runtime defaults**: set default duration, volume, and default track from the UI
- **Clean stop**: fade-out then quit the cast app so speakers release properly

## ⚙️ Requirements
- Windows 10/11 or Linux/Mac (tested on Windows)
- Python 3.10+  
- Google Home / Nest speakers on the **same Wi-Fi** as the computer running this app
- iPhone/Android or any browser to open the web UI

## 📦 Install
```bash
# 1) clone
git clone https://github.com/<your-username>/adhan-cast.git
cd adhan-cast

# 2) (optional) create virtual env
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

# 3) install deps
pip install -r requirements.txt
