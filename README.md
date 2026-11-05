# Azan wa Salawat - أذان وصلوات

A small desktop widget for Windows 10 and 11: today's prayer times, a countdown to the next prayer, and a
notification at each prayer time and shortly before it. One small file, no installation, works offline.

## Download

**Website: [mohmfg17-lab.github.io/azan-wa-salawat](https://mohmfg17-lab.github.io/azan-wa-salawat/)**, with a
Download button for the latest version.

Or open **[Releases](../../releases/latest)** and download the `.zip`. Inside is the app and a "Read me first" file.

1. Unzip and copy `AzanWidget.exe` to a folder you keep, for example Documents.
2. Double-click it. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**
   (see below why this appears).
3. Right-click the widget for settings: location, calculation method, notifications, theme, transparency, and more.

## The "Windows protected your PC" warning

Windows shows this warning for new apps that are not signed with a publisher's certificate. It does not mean a
problem was found in the app. To open it, click **More info**, then **Run anyway**.

A Microsoft Store version is being prepared. Apps in the Store are signed by Microsoft, so the Store version will
open without this warning.

If Windows instead says "An Application Control policy has blocked this file", **Smart App Control** is turned on.
It has no "Run anyway" option, so this download can't run on that PC. The Store version will work there.

## Windows only, for now

The widget is built as a small Windows desktop app. It runs with nothing to install because it uses what Windows
already has. A Mac version needs a separate build, and a Mac to build and test it on. Mac support is planned; there is
no date yet.

## Updates

The widget checks this page once a day. When there is a new version, it shows "New version X — click to download" at
the top of the widget (a coloured dot when minimized). Click it to come here and download the new version. You can
turn the check off in the menu.

This repository holds the releases, and the website's files in the `gh-pages` branch.
