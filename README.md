# PA

PA is a Windows 11 assistant that answers your questions and does things on your PC, privately, with an AI model
that runs on the PC itself.

- Ask anything: questions, writing, advice, and follow-ups, with full answers in PA's own chat, in a small panel or
  full screen.
- Do things: open and close apps, find files and the biggest ones, free up space, change the volume, brightness, or
  dark mode, take a screenshot, set reminders and timers, and check battery, storage, memory, and processor use.
  Anything else becomes a PowerShell command that PA shows you and runs only after you approve it.
- Sort a folder into a new sorted copy, digest a folder into one page of notes, or summarize a PDF or Word document.
- See what's waiting for you in Gmail, Outlook, or GitHub, as a short note on your PC.
- Ask by typing, by holding the mic button (speech is turned into text on your PC), or by dropping a file on the panel.

Every job shows you exactly what it will read and write before it starts. File jobs run in a sandbox with no network
access. Undo moves what PA made to the Recycle Bin.

## Install

Download `PAAgent-win-Setup.exe` from the [latest release](https://github.com/amdradteam2-coder/pa-releases/releases/latest)
and run it. PA installs for your Windows account only (no administrator prompt) and updates itself from this page.

Requires Windows 11 24H2 or later.

The installer is not code-signed yet, so Windows SmartScreen may say it doesn't recognize the app. Choose
**More info**, then **Run anyway**.

## Privacy

PA has no servers and no account, and sends nothing about you anywhere. See the
[privacy policy](https://amdradteam2-coder.github.io/pa-releases/privacy.html).

## Uninstall

Settings › Apps › Installed apps › PA › Uninstall. This removes the app and any Google sign-in it saved (and asks
Google to revoke it). Your notes in `Documents\PA` stay.

## Questions and problems

Open an [issue](https://github.com/amdradteam2-coder/pa-releases/issues).
