# Mi TV 4A Remote Control & Media Cast App

This repository contains all necessary files to run a custom web-based remote control and media casting app for the **Mi TV 4A (32-inch)**.

## Project Structure
- `index.html`: The core app with custom D-Pad controls and media URL casting.
- `.github/workflows/build.yml`: GitHub Actions automated deployment file for GitHub Pages.
- `windows/run_windows.bat`: Quick-launcher script to open the controller interface on Windows desktop.
- `README.md`: Project documentation and setup steps.

## How to Deploy to GitHub Pages
1. Upload all files from this folder to your GitHub repository.
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Set **Source** to **GitHub Actions** (or select the `main`/`master` branch under **Build and deployment**).
4. Save and wait 1–2 minutes. Your live remote control site will be hosted automatically!

## Connecting to Mi TV 4A
1. Connect your phone or PC to the **same Wi-Fi network** as your Mi TV.
2. Check your TV's IP address under **Settings** > **Network & Internet**.
3. Type the IP address into the app interface and send remote commands or cast video URLs.
