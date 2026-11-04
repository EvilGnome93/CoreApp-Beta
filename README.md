# CoreApp beta

CoreApp is a fullscreen Windows hub for your pc: your games, Discord, AI chats, media and live pc stats in one place.

This repo only holds the beta installers, for people who help test. The source code follows with the public release, under GPL-3.0.

## Install

**[Download CoreApp-win-Setup.exe](https://github.com/EvilGnome93/CoreApp-Beta/releases/latest/download/CoreApp-win-Setup.exe)** (about 125 MB, Windows 10 or 11, 64-bit)

CoreApp isn't signed yet, so Windows shows a warning. Choose "More info" and then "Run anyway".

The app installs without admin rights and updates itself from this repo.

## Good to know

- **It's a beta.** Things can break. You can uninstall it at any time in the app or in Windows Settings.
- **Sensors are optional.** For CPU temperature and fps, CoreApp installs a small service with admin rights. Windows asks for permission first, and the PawnIO driver is installed if it's missing. Everything else works without it.
- **No account and no telemetry.** Nothing about what you do goes to the maker. The privacy text is in the app, under ~/settings.

## Found a problem?

Open an [issue](https://github.com/EvilGnome93/CoreApp-Beta/issues) with a screenshot, your CPU and GPU, and what you did. Logs are in `%AppData%\CoreApp\logs`. They can contain your Windows name, so check them before you share them.

## Nederlands

Dit is de testversie van CoreApp. Download de installer hierboven. Windows waarschuwt omdat de app nog niet ondertekend is: kies "Meer informatie" en dan "Toch uitvoeren". De taal kies je in het eerste scherm van de app.
