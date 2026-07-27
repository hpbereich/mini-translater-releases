# Mini Translator

A small translation tool for Windows. No installation is required.

## Download

1. Open the [latest release](https://github.com/hpbereich/mini-translater-releases/releases/latest).
2. Download `MiniTranslator.exe`.
3. Move it to a permanent folder and run it.

Windows may show a SmartScreen warning because the app is not code-signed.
Choose **More info**, check that the file came from this repository, then
select **Run anyway**.

## Basic use

1. Choose the source and target languages.
2. Select a translation service.
3. Enter or paste some text.
4. Click **Translate**.

Google Translate works without an API key. DeepL, Gemini, and OpenAI require
their own API keys. Keys can be saved under **Settings** and are encrypted
using Windows DPAPI.

## Translate selected text

Select text in another application and press `Ctrl+Shift+T`. The optional
floating button can also be enabled or paused from **Settings** or the tray
menu.

Automatic selection capture is disabled in known terminal and remote-control
applications to avoid interfering with their keyboard shortcuts.

## Settings and updates

Open **Settings** to change startup behavior, opacity, translation services,
API keys, and automatic update checks.

When an update is available, Mini Translator can download and replace the
current executable. If Windows displays an error immediately after an update,
close it and start `MiniTranslator.exe` manually.
