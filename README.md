# newkrix Releases & Distribution

Official release repository and distribution endpoint for [**newkrix**](https://github.com/KallelGaNewk/newkrix), a native Matrix desktop client built with Tauri v2, Rust, and Vue 3.

## Downloads & Releases

All desktop installers and release packages are hosted on the GitHub Releases page:

📦 **[Browse Releases & Downloads](https://github.com/KallelGaNewk/newkrix-releases/releases)**

### Windows
- `.exe` NSIS installer (recommended)
- `.msi` Windows Installer
- Tauri Updater delta & signature bundles

## In-App Auto Updates

Newkrix comes with built-in automatic updates powered by the Tauri v2 Updater plugin.
- **Update Manifest**: Hosted automatically at [`latest.json`](https://github.com/KallelGaNewk/newkrix-releases/releases/latest/download/latest.json)
- **Security & Integrity**: Every release binary is cryptographically signed using Minisign. The app validates each update payload signature against the official public key prior to staging or applying updates.

### Public Key
```
dW50cnVzdGVkIGNvbW1lbnQ6IG1pbmlzaWduIHB1YmxpYyBrZXk6IDUxREQwMTBGRUY2NkQ1N0EKUldSNjFXYnZEd0hkVVZSRnZsUEJpNjgxNS9rSC9JVjdDK3JzQVlLWGJ5eEJuUXJKNlZTd0xWYmgK
```

---

© 2026 newkrix. Distributed under the MIT License.
