# Stoic Quote README

A simple extension that fetches a random quote from stoicquotesapi.com and displays it in a modal on Vscode onStartupActivationComplete. It disposes of itself after dismissing, to not consume background memory.

## Features

\!\[modal example\]\(images/stoic-quote-modal-example.png\)

## Requirements

This extension depends on node-fetch

## Extension Settings

In a future release, you will be able to mofidy these settings:
Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

- `stoicode.enable`: Enable/disable this extension.
- `stoicode.modal`: If false, quote will be shown in a less prominent InformationWindow
- `stoicode.buttonText`: Change the button text

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes

Initial release.

### 1.0.0

Initial release of ...

**Enjoy!**
