# 30 Day Demand Renamer releases

This public repository contains signed release files and update metadata for **30 Day Demand Renamer**.

## Current version

Version **2.0.1**

The Windows installer is signed by **Yorgelis Echavarria**. This repository does not contain the application's source code, user settings, PDFs, or client information.

## Installing an internal release

1. Download the signed installer from the latest GitHub release.
2. Install the public certificate on an authorized office computer if Windows has not trusted it yet.
3. Run the installer and verify that Windows shows **Yorgelis Echavarria** as the publisher.

The application checks `release-manifest.json` for updates. It only opens this GitHub release page after the user chooses to view an available update; it does not install updates automatically.
