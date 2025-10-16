# 🟩 Install Stable (LTS) Node.js on Ubuntu

This guide explains how to install the stable (LTS) version of Node.js on Ubuntu easily using NodeSource.

## ⚙ Step 1: Update System Packages
Update your system to make sure all existing packages are up to date.
sudo apt update
sudo apt upgrade

## 📦 Step 2: Install curl (Required Tool)
curl helps in downloading the Node.js setup script.
sudo apt install curl

## 🪄 Step 3: Add NodeSource LTS Repository
Download and run the NodeSource setup script for the LTS (Long Term Support) version of Node.js.
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -

## 📥 Step 4: Install Node.js (Stable Version)
Now install Node.js and npm using the APT package manager.  
This will automatically include npm (Node Package Manager).
sudo apt install nodejs

## 🔍 Step 5: Verify Installation
Check the installed versions of Node.js and npm.
node -v
npm -v
(You should see an LTS version like v20.x.x)

## 🧹 Step 6: Uninstall Node.js (If Needed)
To remove Node.js and npm completely from your system:
sudo apt purge nodejs
sudo apt autoremove

## 🧾 Step 7: Confirm LTS Version
You can verify whether your Node.js version is LTS by running:
node -v
Then check the version on the official site:
https://nodejs.org/en/download  
If it matches the LTS version listed there, you’re all set!

## ✅ Done!
You’ve successfully installed the stable (LTS) version of Node.js on Ubuntu.  
You can now start building and running Node.js applications confidently.
