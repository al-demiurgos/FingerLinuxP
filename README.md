# FingerLinuxP

Open-source installer, compatibility layer and setup tools for Synaptics Validity fingerprint readers on modern Linux distributions.

## Overview

FingerLinuxP is a community-maintained project that provides installation scripts, compatibility fixes, and documentation for running Synaptics Validity fingerprint readers on modern Linux distributions.

The project builds upon the excellent python-validity driver and focuses on making it easier to install, configure, and maintain on current systems such as Debian 13.

**Currently tested on:**

- Lenovo ThinkPad T480
- Debian 13 (Trixie)

## Features

- ✅ Automatic installation
- ✅ Debian 13 (Trixie) support
- ✅ ThinkPad T480 tested
- ✅ open-fprintd integration
- ✅ Suspend/resume support
- ✅ PAM integration
  - sudo
  - login
  - lock screen
- ✅ GPL-3.0 License

## Roadmap

- [ ] Support additional ThinkPad models
- [ ] Support more Linux distributions
- [ ] Automatic package builder (.deb)
- [ ] DKMS packaging (if ever required)
- [ ] GitHub Actions CI
- [ ] Better error diagnostics
- [ ] Installer/uninstaller scripts

## Credits

This project builds upon the original **python-validity** project and the work of the **open-fprintd** community. FingerLinuxP focuses on compatibility, packaging, documentation, and long-term maintenance for modern Linux systems.

## License

GPL-3.0
