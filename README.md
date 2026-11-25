# Personal PDF Suite — Linux Edition (Arch Linux / Desktop)

Native Linux desktop PDF suite engineered for **Arch Linux** and major Linux distributions using **Python + PySide6 (Qt6) / GTK + PyMuPDF (MuPDF)**, with headless `xvfb` GUI testing and packaging via GitHub Actions.

## Planned Architecture & Packaging
- **Engine**: Native C MuPDF (`PyMuPDF`) for crisp rendering, vector text block editing, reflow, redactions, split/merge, watermarks, signatures, and AES-256 encryption.
- **UI**: Native Qt6 (`PySide6`) / GTK integration supporting Wayland & X11.
- **Distribution**: Arch Linux `PKGBUILD` and portable `.AppImage` built by `.github/workflows/build-linux.yml`.

## Running on Arch Linux
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m app.main
```
