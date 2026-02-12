# Fully Kiosk Browser Setup Guide for Android Tablets

This guide provides step-by-step instructions for configuring an Android tablet with Fully Kiosk Browser in single-app kiosk mode.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Step 1: Initial Android Tablet Configuration](#step-1-initial-android-tablet-configuration)
- [Step 2: Installing Fully Kiosk Browser](#step-2-installing-fully-kiosk-browser)
- [Step 3: Configuring Fully Kiosk Cloud](#step-3-configuring-fully-kiosk-cloud)

---

## Prerequisites

- Android tablet (Samsung or compatible device)
- Wi-Fi network credentials
- Google account credentials (provided below)
- Active internet connection

### Account Credentials

**Google Account:**
- Email: `feedback-portal@sanicus-connect.com`
- Password: `mxb$2qEs6FZh@Z`

---

## Step 1: Initial Android Tablet Configuration

### 1.1 Language and Region Setup

1. Power on the tablet and select your preferred language
2. Click **Next**
3. Select your country or region

   ![Country/Region Selection](images/image_2.jpeg)

4. Click **Restart** when prompted

### 1.2 Initial Boot and Licensing

1. Wait for the device to display the boot screen (Samsung logo or manufacturer branding)

   ![Boot Screen](images/image_3.jpeg)

2. After restart, check the box for "I agree to End User License Agreement"

   ![License Agreement](images/image_4.jpg)

3. Click **Next**

### 1.3 Device Setup Method

1. On the "Easy setup with another device" screen, select **Set up manually**

   ![Setup Method](images/image_5.jpeg)

### 1.4 Network Configuration

1. Connect to your Wi-Fi network by selecting it from the available networks list

   ![Wi-Fi Setup](images/image_6.jpeg)

2. Enter the Wi-Fi password when prompted
3. Wait for the "Getting your tablet ready..." screen to complete

   ![Getting Ready](images/image_7.jpeg)

### 1.5 Data Transfer Options

1. When prompted to "Copy apps and data," select **Don't copy**

   ![Copy Apps and Data](images/image_1.jpeg)

### 1.6 Google Account Setup

1. On the Google Sign-in page, enter the credentials:
   - Email: `feedback-portal@sanicus-connect.com`
   - Password: `mxb$2qEs6FZh@Z`

   ![Google Sign-in](images/image_8.jpeg)

2. Accept the Terms of Service

   ![Terms of Service](images/image_9.jpeg)

3. Wait for "Getting your Account info" to complete

   ![Account Info](images/image_10.jpeg)

### 1.7 Security Configuration

1. On the "Protect your Tablet" screen, select **PIN**

   ![Protect Your Tablet](images/image_11.jpeg)

2. Set the PIN to `0000` (or another simple combination)
3. When warned about using a simple PIN, click **Use anyway**

   ![PIN Warning](images/image_12.jpeg)

### 1.8 Privacy Settings

1. On the Google Services page, **uncheck all blue boxes** so they appear grey

   ![Google Services - Unchecked](images/image_13.jpeg)

2. Click **Accept**
3. On the search engine selection screen, click **Next**

   ![Search Engine](images/image_14.jpeg)

4. Select **Google** from the list of search engines

   ![Select Google](images/image_15.png)

5. Click **Set as default**

### 1.9 Samsung Account Configuration

1. When prompted to sign into a Samsung Account, click **Sign in with Google**

   ![Samsung Sign-in](images/image_16.jpeg)

2. On the Samsung services page, ensure **only** the Terms and Conditions checkbox at the top is checked

   ![Samsung Services - First Page](images/image_17.jpeg)

3. Click **Agree**
4. On the following page, uncheck all boxes

   ![Samsung Services - Second Page](images/image_18.jpeg)

5. Click **Agree**

### 1.10 Final Setup Steps

1. On the "Recommended apps" page, select **Samsung account**

   ![Recommended Apps](images/image_19.jpeg)

2. Click **Next**
3. When you see "You're all set up!", click **Home**

   ![Setup Complete](images/image_20.jpeg)

4. On the "Discover and install great apps" screen, click the **X** in the top-right corner to dismiss

   ![Discover Apps](images/image_21.jpeg)

5. You should now be on the tablet's home screen

---

## Step 2: Installing Fully Kiosk Browser

### 2.1 Initial Browser Configuration

1. Open **Google Chrome** on the tablet
2. When prompted, click **Continue as Feedback**

   ![Continue as Feedback](images/image_22.jpeg)

3. Confirm by clicking **Continue** again

   ![Confirm Sign-in](images/image_23.jpeg)

4. When asked to sync history and tabs, select **No, thanks**

   ![Sync Settings](images/image_24.jpeg)

5. On the "Turn on an ad privacy feature" page, select **No, thanks**

   ![Ad Privacy](images/image_25.jpeg)

### 2.2 Downloading the APK

1. Navigate to [https://www.fully-kiosk.com/en/](https://www.fully-kiosk.com/en/)
2. Locate and download **Fully Single App Kiosk APK** from the right side of the page

   ![Fully Kiosk Download Page](images/image_26.jpeg)
   
   > **Note:** The version number may vary from screenshots

3. If you receive a security warning, click **Download anyway**

   ![Download Warning](images/image_27.jpeg)

4. Once downloaded, click **Open**

   ![Open APK](images/image_28.jpeg)

### 2.3 Installation Permissions

1. If this is your first sideloaded APK installation, you'll see a security warning

   ![Security Warning](images/image_29.jpeg)

2. Click **Settings** when prompted
3. Toggle the permission switch to **Allow** (the switch should turn blue)

   ![Allow Installation](images/image_30.jpeg)

4. Complete the APK installation

---

## Step 3: Configuring Fully Kiosk Cloud

### 3.1 Account Creation

1. Navigate to [https://cloud.fully-kiosk.com/cloud/](https://cloud.fully-kiosk.com/cloud/)

   ![Fully Kiosk Cloud Login](images/image_31.jpeg)

2. Click **Create new account**

   ![Create Account](images/image_32.jpeg)

3. Complete the registration form
4. Check your email (including spam folder) for the verification message
5. Verify your account via the email link
6. Log in to the Fully Kiosk Cloud portal

### 3.2 Device Management

1. After logging in, you'll be directed to the "Fully Kiosk Devices" page

   ![Devices Page](images/image_33.jpeg)

2. Click the **menu icon** (≡) in the top-left corner
3. Select **Files** from the side menu

### 3.3 APK Upload

1. In the Files section, click **Upload File**
2. Select the downloaded "Fully Single App Kiosk APK" file
3. Wait for the upload to complete

---

## Troubleshooting

### Common Issues

**Installation blocked:** Ensure "Install from unknown sources" is enabled for Chrome in Settings > Security > Unknown sources

**APK won't install:** Verify you downloaded the correct APK file (Fully Single App Kiosk, not the standard version)

**Cloud connection issues:** Check that the tablet has a stable internet connection and that firewall settings aren't blocking the connection

---

## Support

For additional support and documentation:
- Official Documentation: [https://www.fully-kiosk.com](https://www.fully-kiosk.com)
- Cloud Portal: [https://cloud.fully-kiosk.com](https://cloud.fully-kiosk.com)

---

## Security Considerations

> **Warning:** This guide includes plaintext credentials for demonstration purposes. In production environments:
> - Use unique, strong passwords
> - Enable two-factor authentication where available
> - Rotate credentials regularly
> - Follow your organization's security policies

---

## License

This setup guide is provided for educational and deployment purposes. Fully Kiosk Browser is a commercial product subject to its own licensing terms.
