# 🔍 Shodan Juicy Info Extractor

A one-page browser-based tool to extract juicy data from raw Shodan HTML/text output. Ideal for bug bounty, OSINT, and recon tasks.

## ⚡ Features

- 🧠 Extracts:
  - IP Address, Hostname, Organization
  - Country & City/Region
  - TLS Versions, SSL Certificate CN/Org/Issuer
  - HTTP Status Code & Server Header
  - Redirect URLs, SSL Errors, SMTP Banner
- 📥 Import/Export XLSX
- 💾 Auto Save & Load (localStorage)
- 🧹 Clear Progress Button
- 🎨 Clean Tailwind UI, responsive & portable
- 🛡 100% client-side — your data stays local

## 🚀 Usage

1. Open `index.html` in your browser.
2. Paste raw Shodan page (HTML/text).
3. Click **Extract 🔓**.
4. View, filter, export, import, or clear your data.

## 🗂 Example Output

| IP           | Org         | TLS      | HTTP    | Redirect              |
|--------------|-------------|----------|---------|------------------------|
| 104.21.9.10  | Cloudflare  | TLSv1.3  | 200 OK  | https://example.com    |

## 📁 Structure

- `index.html` – Main tool
- `README.md` – Project info

## 🛠 Built With

- Tailwind CSS
- SheetJS (xlsx)
- Vanilla JavaScript

## 📌 Notes

- No server, database, or backend needed.
- Use it offline, privately, and freely.
- Built for fast recon and organized exports.

## 📃 License

MIT License • Made with ❤️ by [H4K2LIV3](https://hacktolive.net)
