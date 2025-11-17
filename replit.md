# Cookie Clicker - Replit Import

## Overview
This is a mirror of the classic Cookie Clicker game by Orteil (http://orteil.dashnet.org/cookieclicker/). The game is a purely client-side HTML/CSS/JavaScript incremental game where players click cookies to earn more cookies and purchase upgrades.

## Project Structure
- **Frontend**: Pure HTML/CSS/JavaScript static files
- **Server**: Simple Python HTTP server for serving static content
- **Assets**: 
  - `/img/` - Game images and sprites
  - `/snd/` - Sound effects
  - `/loc/` - Language translations
  - JavaScript files: `main.js`, `ajax.js`, `base64.js`, minigame files, etc.

## Current State
- **Version**: 2.052
- **Server**: Running on Python 3.11 HTTP server
- **Port**: 5000 (configured for Replit webview)
- **Deployment**: Configured for autoscale deployment

## Setup Details
The project uses a custom Python HTTP server (`server.py`) that:
- Serves static files from the project root
- Runs on `0.0.0.0:5000` for Replit compatibility
- Includes proper cache-control headers to prevent caching issues
- Is configured as a workflow for automatic restart

## Recent Changes (2024-11-12)
- Imported from GitHub repository
- Created `server.py` for serving static files
- Configured workflow for webview on port 5000
- Set up deployment configuration for autoscale
- Added `.gitignore` for Python artifacts
- Created project documentation

## How to Update the Game
See the original README.md for instructions on updating game assets and code from the upstream source. The update process involves fetching new images, sounds, translations, and JavaScript files using wget commands.

## Notes
- This is an educational mirror of the original game
- All code and graphics copyright Orteil, 2013-2023
- External ads and analytics may show 403 errors (expected behavior)
- The game stores progress in browser localStorage
