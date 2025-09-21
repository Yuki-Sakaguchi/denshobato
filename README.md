# Denshobato

<div align="center">
  <img src="./assets/extension_icon.png" width="180">
</div>

A Raycast extension that helps avoid garbled characters and input errors when using IME (Input Method Editor). Denshobato provides a dedicated input form that sends text directly to the focused application while also saving it to your clipboard.

## Why Use Denshobato?

### The Problem
Every application has different input behaviors that can frustrate users:

- **Inconsistent Submit Actions**: Is it Enter or Shift+Enter? You never know until you accidentally send an incomplete message
- **IME Compatibility Issues**: Japanese, Chinese, Korean, and other IME inputs often malfunction in CLI tools, AI chat interfaces, and terminal applications
- **Input Field Limitations**: Some applications have quirky text input behaviors that interfere with natural typing
- **Accidental Submissions**: Different apps handle line breaks differently, leading to premature message sending

### The Solution
Denshobato provides a **consistent, reliable input environment** that works the same way every time:

- ✅ **Predictable Behavior**: Always submit when you mean to submit
- ✅ **IME-Friendly**: Perfect compatibility with all input methods
- ✅ **Universal Compatibility**: Works with any application that accepts text input
- ✅ **Safe Backup**: Your text is always saved to clipboard as insurance

## Features

- **Smart Text Input**: Enter text in a dedicated form that bypasses IME-related issues
- **Direct Application Integration**: Automatically sends text to the currently focused application
- **Clipboard Integration**: Automatically saves text to your clipboard for backup and convenience
- **Fallback Support**: Gracefully handles permission issues with multiple fallback methods
- **Cross-Application Compatible**: Works with any application that accepts text input

## How It Works

1. **Launch Denshobato** from Raycast
2. **Enter your text** in the provided text area
3. **Submit** - Denshobato will:
   - Attempt to paste text directly to the focused application using Raycast's clipboard API
   - If direct paste fails, use AppleScript to simulate Cmd+V keystroke
   - Always save the text to your clipboard as a backup
   - Restore your original clipboard content after operation

## Installation

Install Denshobato from the [Raycast Store](https://www.raycast.com/store).

1. Open Raycast
2. Search for "Denshobato" in the extensions
3. Click "Install Extension"

Alternatively, you can search for "Denshobato" directly in Raycast and install it from the search results.

## Usage

### Basic Usage
- Open Raycast and search for "Denshobato" or "Write a letter"
- Enter your text in the text area
- Press Enter or click Submit
- The text will be sent to the focused application

### Permission Requirements
- **Accessibility Access**: Required for AppleScript automation
- If accessibility permissions are not granted, Denshobato will still copy text to your clipboard with a notification

## License

MIT License - see LICENSE file for details

## Support

For issues and feature requests, please create an issue in the GitHub repository.
