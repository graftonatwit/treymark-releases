# Treymark

Point at it. Your agent fixes it.

Leave notes right on your running web app: click an element or drag a box,
type what should change, and send it. Your coding agent (Claude Code, Codex,
Cursor, or any agent with a shell) reads the note with the exact element,
selector and position, makes the change, and replies on the note. Reply again
to keep refining.

## Download

Windows: download `Treymark-Setup-<version>.exe` from the latest release:
https://github.com/graftonatwit/treymark-releases/releases/latest

The installer is not code signed yet, so Windows may show
"Windows protected your PC". Click **More info**, then **Run anyway**.

## Get started

1. Open Treymark and choose your project folder.
2. Add Treymark to your page: load the Chrome extension from the folder shown
   in the app (chrome://extensions, Developer mode, Load unpacked), or paste
   the script tag the app gives you.
3. Open the **Connect agent** tab, copy the setup for your agent, and install
   the Treymark skill.
4. Press Alt+A on your localhost page, click anything, and describe the change.
   Then tell your agent: "check my Treymark notes".

## Privacy and security

- Everything runs on your computer. Notes are stored in a `.treymark` folder
  inside your project.
- No accounts, no telemetry. Treymark never sends your notes or code anywhere.
- The local server only listens on 127.0.0.1 and only accepts requests from
  localhost pages or your agent's private token.

## Feedback

Found a bug or have an idea? Open an issue in this repo.

Treymark is free to use under the license in LICENSE.txt.
© 2026 Trevor Grafton
