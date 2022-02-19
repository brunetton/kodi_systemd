Systemd service for Kodi.

- start at boot
- restart in case of crashes

## Install

- copy `kodi.service` to systemd custom scripts path (`/etc/systemd/system/` on Debian an deviated)
- Don't forget to enable this service to make Kodi start on each boot:

        systemctl enable kodi
