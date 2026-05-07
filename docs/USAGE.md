# Usage Guide

## Overview

ReceiptsAT makes it easy to generate and manage rent receipts through Portugal's Tax Authority portal. This guide covers all the main features and workflows.

## 📋 Table of Contents

- [Generating a Receipt](#generating-a-receipt)
- [Viewing Receipt History](#viewing-receipt-history)
- [Exporting to CSV](#exporting-to-csv)
- [Managing Your Account](#managing-your-account)
- [Tips & Best Practices](#tips--best-practices)

---

## Generating a Receipt

### Step 1: Open the Application

1. Launch **PortalReceiptsApp** from your desktop or Start menu
2. If not already logged in, enter your Portal das Finanças credentials
3. The main dashboard will load

### Step 2: Fill in Receipt Details

1. Click **"New Receipt"** button
2. Enter the following information:
   - **Tenant Name** - Full name of the person paying rent
   - **Tenant NIF** (Optional) - Tax ID of the tenant
   - **Rent Amount** - Total rent paid (in €)
   - **Rent Month** - Month/year the rent covers
   - **Payment Date** - Date the rent was paid
   - **Payment Method** - Cash, Bank Transfer, Check, etc.

### Step 3: Add Details (Optional)

- **Property Address** - Where the rental property is located
- **Notes** - Any additional information about the payment
- **Frequency** - One-time or recurring monthly receipt

### Step 4: Generate Receipt

1. Click **"Generate Receipt"**
2. The application will communicate with Portal das Finanças
3. Your receipt will be generated with an official reference number
4. A confirmation message will appear on screen

### Step 5: Download Receipt

1. After generation, click **"Download PDF"**
2. Choose your save location (default: Downloads folder)
3. The receipt will be saved as `Receipt_[Reference_Number].pdf`
4. You can now print or share this PDF

---

## Viewing Receipt History

### Access Your Receipt History

1. Click **"History"** or **"View Receipts"** tab
2. All previously generated receipts will be displayed in a table showing:
   - Receipt Reference Number
   - Tenant Name
   - Rent Amount
   - Date Generated
   - Status (Confirmed, Pending, etc.)

### Search & Filter

- **Search by Tenant Name** - Use the search box to find receipts
- **Filter by Date Range** - Select start and end dates
- **Filter by Status** - View only confirmed, pending, or rejected receipts

### View Receipt Details

1. Click on any receipt in the history list
2. A detailed view will open showing:
   - Full receipt information
   - Tenant details
   - Payment confirmation
   - Official Tax Authority reference number

---

## Exporting to CSV

### Export All Receipts

1. Go to **"History"** tab
2. Click **"Export"** button (top right)
3. Choose **"CSV Format"** from the dropdown
4. Select your save location
5. Click **"Save"**

### Use in Excel/Spreadsheet

The CSV file includes:
- Receipt Reference Number
- Tenant Name & NIF
- Rent Amount
- Payment Date
- Generation Date
- Status

You can now open this file in Excel, Google Sheets, or any spreadsheet application for further analysis or record-keeping.

---

## Managing Your Account

### View Account Information

1. Click **"Settings"** or your profile icon (top right)
2. View your connected Portal das Finanças account details:
   - Your Tax ID (NIF)
   - Account name
   - Last sync date

### Change Password

1. Go to **"Settings"** → **"Security"**
2. Click **"Change Password"**
3. Enter your new Portal das Finanças password
4. The app will sync with the new credentials

### Logout

1. Click **"Settings"** → **"Logout"**
2. You will be returned to the login screen
3. To use the app again, enter your credentials

### Clear Local Data

1. Go to **"Settings"** → **"Advanced"**
2. Click **"Clear Cache"** (removes temporary files)
3. Click **"Clear History"** (removes local receipt history)
4. Note: This does NOT delete receipts from Portal das Finanças

---

## Tips & Best Practices

### ✅ Dos

- **Keep records** - Always download and save PDF receipts
- **Use consistent names** - Helps when searching history
- **Regular exports** - Export to CSV monthly for backup
- **Verify details** - Double-check tenant information before generating
- **Update password** - Change Portal das Finanças password regularly

### ❌ Don'ts

- **Don't share credentials** - Keep your login information private
- **Don't generate duplicate receipts** - Check history before creating new ones
- **Don't rely on local storage alone** - Always backup to PDF
- **Don't clear history** - Unless you've backed up receipts

### 🔐 Security Tips

- **Enable 2FA** on your Portal das Finanças account
- **Logout** when finished using the app
- **Keep your computer updated** with the latest Windows patches
- **Store PDF receipts** in a secure location with regular backups

### 📊 Monthly Workflow

1. **Beginning of month** - Generate receipts for previous month's payments
2. **Mid-month** - Export CSV for accounting records
3. **End of month** - Backup all PDFs to external storage
4. **Quarterly** - Review history and reconcile with Portal das Finanças

---

**Need help?** Check the [Troubleshooting Guide](./TROUBLESHOOTING.md).

**Installation issues?** See the [Installation Guide](./INSTALL.md).
