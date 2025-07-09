# WireGuard Config to V2Ray Link Converter 🛡️🔗

A clean and easy-to-use web tool that converts WireGuard `.conf` configuration files into `wireguard://` links — perfect for quick sharing or mobile import.

## ✨ Features

- 🔄 Converts multiple `.conf` files at once
- 📂 Drag & Drop support for easy file input
- 📋 One-click copy for all generated links
- ✅ Real-time feedback with user-friendly messages
- 🔒 All processing happens locally in the browser — no data is sent to any server
- 🌐 Fully responsive and mobile-friendly design

## 🚀 How to Use

1. Open [the app (WireGuard to V2Ray)](https://yasinc2.github.io/wireguard-to-v2ray/) file in your browser.

2. Drag and drop one or more `.conf` files into the app, or click to select them.

3. Click **"Convert Files"** to generate the `wireguard://` links.

4. Use the **"Copy All Links"** button to copy them to your clipboard.


## 🧪 Example Link Format

The generated links follow this structure:

```
wireguard://<PrivateKey>@<Endpoint>?address=<Address>&publickey=<PublicKey>&mtu=<MTU>#Filename
```

## 📜 License

This project is open source and licensed under the [MIT License](LICENSE).