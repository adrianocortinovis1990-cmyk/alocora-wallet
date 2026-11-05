# Alocora Wallet — design

Design files for **Alocora Wallet**, a virtual wallet for managing expenses, budgets, savings, projects and documents, with separate Business, Personal and Family profiles.

## What's inside (`project/`)

| Area | Files |
|---|---|
| Landing pages | `Landing.dc.html` (web), `LandingMobile.dc.html` (mobile) |
| Log in | `Login.dc.html` (web), `MobileLogin.dc.html` (mobile) |
| Welcome / splash | `Welcome.dc.html` |
| Choose profile | `ChooseProfile.dc.html` (web), `MobileChoose.dc.html` (mobile) |
| Web app | `Main.dc.html` (+ `MainPersonal`, `MainFamily`), `Projects.dc.html`, `Plan.dc.html`, `Documents.dc.html`, `Settings.dc.html` |
| Mobile app | `Mobile.dc.html` (+ `MobilePersonal`, `MobileFamily`), `MobileAdd.dc.html`, `MobileDocs.dc.html`, `MobileSettings.dc.html` |
| AI assistant | `AiChat.dc.html` |
| Assets | `alocora-logo.png` |
| Canvas layout | `canvas.json` |

## Notes

These are Claude Design artboard files (`.dc.html`). They use the Claude Design runtime (`support.js`), which is not part of this repository, so they are meant as the design source / reference for building the production app rather than pages that run on their own.
