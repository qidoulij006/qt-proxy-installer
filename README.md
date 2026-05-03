# qt-proxy-installer

GitHub installer for the AFX SOCKS5 proxy package.

## Install

```bash
wget https://raw.githubusercontent.com/qidoulij006/qt-proxy-installer/main/install-proxy-from-github.sh -O qt-install.sh
cat qt-install.sh
chmod +x qt-install.sh
sudo ./qt-install.sh
```

The installer uses these defaults:

- SOCKS5 username: `afx`
- SOCKS5 password: auto-generated 8-character password
- Port: `1080`
- Bind address: `0.0.0.0`

The generated password is the SOCKS5 proxy password, not the cloud host login password.
After installation, copy the printed `AFX proxy_url` into the proxy address field.

## Files

- `install-proxy-from-github.sh`: downloads the packaged installer from this repository and runs it
- `dist/afx-proxy-installer-20260503.tar.gz`: packaged proxy installer bundle
