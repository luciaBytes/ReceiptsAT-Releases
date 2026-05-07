# Troubleshooting Guide

If you encounter issues while using ReceiptsAT, use this guide to troubleshoot and resolve common problems.

---

## 🛡️ Security Warnings

### "Windows protected your PC"

This warning is triggered by Windows SmartScreen because ReceiptsAT is a new application.

1. **Click "More info"**
2. **Click "Run anyway"**
3. The application will launch safely

For more details about Windows SmartScreen, visit Microsoft Support.

---

## 🔑 Login Issues

### Common Problems

1. **Wrong Credentials**:
   - Verify your Portal das Finanças **Tax ID (NIF)** and password.
   - Double-check for typos (case-sensitive fields).

2. **Two-Factor Authentication (2FA)**:
   - Enter the code from your authenticator app or SMS.
   - Ensure your phone is not on airplane mode.

3. **Locked Account**:
   - If your account is locked due to multiple failed attempts, reset your password using the [Portal das Finanças](https://www.portaldasfinancas.gov.pt/) website.

4. **No Internet Connection**:
   - Ensure your device is connected to a stable internet network.

---

## ⚠️ Application Issues

### Application Won't Start

1. **Check System Requirements**:
   - Ensure you have **Windows 10 or Windows 11**.

2. **Restart Your System**:
   - Reboot your computer and try again.

3. **Reinstall the Application**:
   - Uninstall the app:
     - Open **Control Panel → Programs → Programs and Features**
     - Find "PortalReceiptsApp" and click **Uninstall**
   - Download the latest version from the [Releases](../../releases) page.

### Application is Slow/Unresponsive

1. **Clear Cache**:
   - Open **Settings** in the app.
   - Navigate to **Advanced Options**.
   - Select **Clear Cache**.

2. **Check Background Processes**:
   - Close unnecessary programs in Task Manager.

3. **Update Windows**:
   - Ensure your operating system has the latest updates installed.

---

## 📜 Receipt Issues

### Receipt Fails to Generate

1. **Check Internet Connection**:
   - The app needs a stable internet connection to access Portal das Finanças.

2. **Verify Credentials**:
   - Ensure correct login details in **Settings → Account Settings**.

3. **Sync Data**:
   - Go to **Settings → Account Settings** and select **Sync Data**.

### Cannot Export to CSV

1. **Try a Different Location**:
   - Ensure the export folder is not read-only.
   - Use a writable location (e.g., Desktop, Documents).

2. **Verify File Permissions**:
   - Right-click the app and select **Run as Administrator**.

3. **Clear Cache**:
   - Open **Settings → Advanced Options → Clear Cache**.

---

## 💾 Update Problems

### Update Errors

If you face issues updating to the latest version:
1. Download the new installer from [Releases](../../releases).
2. Uninstall the old version before installing the new one.
3. Restart your computer and try running the installer again.

---

**Need More Help?**

If you can’t find a solution here, reach out by:
1. Posting an [Issue on GitHub](../../issues)
2. Contacting support via our portal.
