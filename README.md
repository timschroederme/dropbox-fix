# dropbox-fix

This script fixes the issue that the Dropbox system tray icon will not be properly displayed. The fix is based upon [this discussion](https://askubuntu.com/a/739018).

## Deployment

The script needs to be deployed in `/usr/bin`. The `dropbox-fix.desktop` file needs to be placed in `~/.config/autostart`. 