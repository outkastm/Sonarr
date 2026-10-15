# Sonarr for TOS


## 🛠️ Architecture & Backend Notice

This application consists of a modern frontend web interface paired with a custom proxy backend service designed specifically for TOS7 integration.

> ℹ️ **Backend Dependency & Source Code:**  
> This package includes the backend proxy service compiled directly from source. You can view or inspect the backend daemon source code at the official repository:  
> 🔗 **[outkastm/TOS7_PBD: TOS7 Proxy Backend Daemon](https://github.com/outkastm/TOS7_PBD)**

---

## ✨ WebUI Features

- **TOS7 Integrated Management:** Native dashboard, system diagnostics, and operational controls via TOS7 API.
- **Service Status Monitoring:** Real-time checking of running services and process states.
- **Configuration Editor:** Edit application environment files and options directly from the web interface with automatic JSON syntax validation.
- **Log Viewer:** Built-in viewer for viewing system, startup, and application runtime logs.
- **Privacy & Compliance Standardized:** Full transparent disclosure of local data processing, retention policies, and user rights.

---

## 🚀 Installation on TerraMaster TOS7

- **TOS7 App Center online version:** 
1. Search for Sonarr in App Center.
- **TOS7 App Center manual installation:**
1. Download the latest release `.deb` package from the [Releases page](../../releases) or [TMNASCommunity Downloads](https://tmnascommunity.eu/Sonarr).
2. Open your TerraMaster NAS web desktop and launch the **App Center**.
3. Click on **Settings / Install App Manually** and select the downloaded package.
4. Follow the on-screen prompts to complete the installation.

---

## ⚙️ Configuration & Data Storage

- **Application Directory:** `/usr/local/<appId>/`
- **Permissions:** The application runs under a dedicated service user. Ensure appropriate folder ownership and POSIX permissions are assigned to shared folders accessed by the app.

---

## 📄 License & Privacy

This project is released under the open-source license.  
For full information regarding network data flows, third-party disclosures, retention periods, and security measures, please refer to our integrated **Privacy Policy & Software License Notice** included inside the package.

---

## 🤝 Support & Acknowledgments

- **Package Maintainer:** OutkastM
- **Community Portal:** [TMNASCommunity](https://tmnascommunity.eu)
- **Backend Component:** Built using [TOS7_PBD](https://github.com/outkastm/TOS7_PBD)
