# Add to Chrome

This guide explains how to install and add the Memos Chrome Extension to Google Chrome for development and testing purposes.

## Prerequisites

- Google Chrome browser installed
- The extension files (this repository)

## Installation Steps

1. **Download or Clone the Repository**
   - Download the ZIP file from GitHub and extract it, or clone the repository:

     ```bash
     git clone https://github.com/amirrouh/memos-chrome-extension.git
     ```

2. **Open Chrome Extensions Page**
   - Open Google Chrome
   - Type `chrome://extensions/` in the address bar and press Enter
   - Alternatively, click the three-dot menu → More tools → Extensions

3. **Enable Developer Mode**
   - In the top right corner of the Extensions page, toggle "Developer mode" to ON

4. **Load the Extension**
   - Click the "Load unpacked" button
   - Navigate to and select the folder containing the extension files (the folder with `manifest.json`)
   - Click "Select Folder"

5. **Verify Installation**
   - The extension should now appear in the list of installed extensions
   - You should see the Memos extension icon in your Chrome toolbar
   - Click the extension icon to open the popup and configure it

## Usage

- Click the extension icon in the toolbar to open the Memos posting interface
- Right-click on selected text or links to send them to Memos
- Configure your Memos server URL and API token in the extension settings

## For Production Use

For regular users, the extension is available on the Chrome Web Store at:
<https://chrome.google.com/webstore/detail/memos-bber/cbhjebjfccgchgbmfbobjmebjjckgofe/>

## Troubleshooting

- If the extension doesn't load, ensure all files are present and `manifest.json` is valid
- Check the Chrome developer console for any errors (Extensions page → click "background page" under the extension)
- Make sure your Memos server is accessible and the API token is correct