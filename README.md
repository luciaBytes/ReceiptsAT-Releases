# ReceiptsAT-Releases
Emissão de recibos pelo portal da Autoridade Tributária (Portugal)

## System Requirements

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **RAM:** Minimum 2GB
- **Disk Space:** ~100MB for installation
- **Internet Connection:** Required for Portal das Finanças access
- **No Python Required:** Application is self-contained

## 📥 Installation Steps

### Step 1: Download the Installer

1. Go to the [Releases](../../releases) page
2. Download the latest `PortalReceiptsApp_Setup_v*.exe` file
3. Save it to your preferred location (e.g., Downloads folder)

### Step 2: Run the Installer

1. Double-click `PortalReceiptsApp_Setup_v*.exe`
2. If prompted by Windows Defender or User Account Control, click **"Yes"** or **"Run anyway"**
3. The installer window will open

### Step 3: Follow the Setup Wizard

1. **Welcome Screen** - Click **"Next"**
2. **License Agreement** - Read and click **"I Agree"**
3. **Installation Folder** - Choose your preferred location (default: `C:\Program Files\PortalReceiptsApp`) and click **"Next"**
4. **Start Menu Shortcuts** - Click **"Next"** to create shortcuts
5. **Ready to Install** - Click **"Install"** to begin
6. **Installation Progress** - Wait for completion (~30 seconds)
7. **Finish** - Click **"Finish"**

### Step 4: Launch the Application

After installation, you can launch the app by:
- **Desktop Shortcut** - Double-click the "PortalReceiptsApp" icon on your desktop
- **Start Menu** - Search for "PortalReceiptsApp" and click the result
- **Program Files** - Navigate to `C:\Program Files\PortalReceiptsApp\` and run `PortalReceiptsApp.exe`

## 🔐 First Launch - Authentication

### Setting Up Your Portal das Finanças Login

1. Launch the application
2. Enter your **Portal das Finanças credentials**:
   - Tax ID (NIF)
   - Password
3. If prompted, complete **two-factor authentication**
4. Click **"Login"**
5. The app will verify your credentials and sync your account

## 📋 Using the Application

### Generate a Receipt

1. From the main menu, select **"Generate Receipt"**
2. Enter receipt details:
   - **Tenant Name**
   - **Period** (month/year)
   - **Rent Amount**
   - **Payment Method**
3. Click **"Generate"**
4. The receipt will be created and displayed

### Export to CSV

1. Click **"Export"** 
2. Choose your save location
3. The file will be saved as `receipts_export.csv`

### View Receipt History

1. Select **"History"** from the menu
2. Browse previously generated receipts
3. Click any receipt to view details or regenerate

## 🛠️ Troubleshooting

### "Windows protected your PC" Message

This is a Windows SmartScreen warning. This is normal for new applications.
- Click **"More info"**
- Click **"Run anyway"**

### Application Won't Start

1. Ensure you have **Windows 10 or later**
2. Try restarting your computer
3. Reinstall the application:
   - Uninstall from **Control Panel → Programs → Uninstall a program**
   - Download the latest installer
   - Run the installer again

### Login Issues

1. **Verify credentials**: Ensure your tax ID and password are correct
2. **Check internet**: Confirm you have an active internet connection
3. **2FA Required**: Some accounts require two-factor authentication - have your phone ready
4. **Reset Password**: If you've forgotten your Portal das Finanças password, reset it at [Portal das Finanças](https://www.portaldasfinancas.gov.pt/)

### Application Crashes

1. Try running as Administrator:
   - Right-click the app
   - Select **"Run as administrator"**
2. Update Windows: Check for system updates
3. Reinstall the application

## 🔄 Updating to a New Version

1. Download the new installer from [Releases](../../releases)
2. Run the new installer
3. When prompted about the existing installation, choose **"Upgrade"**
4. The app will update while preserving your settings

## 🗑️ Uninstalling

1. Open **Control Panel** → **Programs** → **Programs and Features**
2. Find **"PortalReceiptsApp"** in the list
3. Click it and select **"Uninstall"**
4. Confirm the uninstall
5. All application files will be removed (settings may be retained)

### Manual
