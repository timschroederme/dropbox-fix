# dropbox-fix

This project fixes the issue that the Dropbox system tray icon will not be properly displayed. The fix is based upon [this discussion](https://askubuntu.com/questions/732816/xubuntu-dropbox-icon-fail).

## Deployment

The `dropbox.desktop` file needs to be deployed in `~/.config/autostart`. Auto-start of Dropbox should be disabled in the settings of the Dropbox client, as the `dropbox.desktop` file will take care of that.