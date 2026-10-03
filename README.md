# JennyApps — Developer Website (`iron-wing-man.github.io`)

Official developer portal and verification website for **JennyApps** on Google Play Console (`com.jennyapps.marginalia`).

Hosted live at: **[https://iron-wing-man.github.io/](https://iron-wing-man.github.io/)**

---

## 📋 Overview & Purpose

This repository hosts the static website serving as the official **Developer Website (網站)** for the Google Play Developer Account **JennyApps**, complying with Google Play identity and merchant verification requirements:

1. **Developer Identity & Presentation**: Transparent developer details (Studio name: JennyApps, Lead Developer: Jasper, Contact: `jasper.wkuk@gmail.com`).
2. **Flagship Application**: Detailed showcase of **Marginalia AI** (`com.jennyapps.marginalia`), an Android AI reading companion designed with a Local-First and ephemeral RAM capture architecture.
3. **Mandatory Legal Pages**:
   - [Privacy Policy (`privacy.html`)](https://iron-wing-man.github.io/privacy.html) — Comprehensive disclosure of ephemeral camera/RAM OCR processing, local SQLite storage, Google Drive AppData sync, and zero central database tracking.
   - [Terms of Service (`terms.html`)](https://iron-wing-man.github.io/terms.html) — Standard terms for mobile application usage and Google Play billing.
4. **Domain & Identity Verification**: Preserves Google site verification (`google3a91c8967ef0ce93.html` and meta tag).

---

## 🗂️ File Structure

```text
iron-wing-man.github.io/
├── index.html                  # Developer home page & Marginalia AI showcase
├── privacy.html                # Google Play compliant Privacy Policy
├── terms.html                  # Terms of Service
├── google3a91c8967ef0ce93.html # Google Search Console / Play Console site verification
├── .nojekyll                   # Bypasses Jekyll processing for standard HTML
├── assets/
│   └── images/
│       ├── marginalia-icon.png # 1024x1024 app icon
│       ├── marginalia-icon.svg # Vector app icon
│       └── hero-banner.jpg     # AI reading companion hero banner
└── README.md
```

---

## 🚀 Deployment

Changes pushed to the `main` branch are automatically deployed by GitHub Pages.