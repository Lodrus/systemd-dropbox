# systemd-dropbox

#### Deploy to
~/.config/systemd/user/

#### Start the service once manually and log in when prompted in a browser
systemctl --user start dropbox

### Set to start when the user logs in
systemctl --user enable dropbox

#### Related commands
systemctl --user status dropbox
journalctl -u dropbox

#### Credit to https://www.bbkane.com/2017/08/04/Dropbox-as-a-systemd-service.html
