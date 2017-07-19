# dropbox-fix

This project fixes the issue that the Dropbox system tray icon will not be properly displayed. The fix is based upon [this discussion](https://askubuntu.com/questions/732816/xubuntu-dropbox-icon-fail).

## Deployment

The `dropbox-fix.desktop` file needs to be deployed in `~/.config/autostart`. Auto-start of the Dropbox client should be disabled in the settings of the Dropbox client, as the `dropbox-fix.desktop` file will take care of that.

The `dropbox-fix.desktop` file may be renamed but its name must not be `dropbox.desktop`, as otherwise the Dropbox client would either overwrite it when it launches (when autostart is enabled in the Dropbox client settings), or remove it (when autostart is disabled).