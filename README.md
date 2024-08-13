# Leads Tracker Chrome Extension
A simple yet powerful Chrome extension designed to help sales executives and anyone who needs to keep track of important websites or tabs. This extension allows users to save URLs, which are stored locally and can be accessed at any time.

## Features
- Save the current tab's URL with a single click.
- Add URLs manually using the input field.
- View saved URLs in a list.
- Open any saved URL in a new tab.
- Clear all saved URLs with a double-click.
## Installation
- To install and use this extension, follow these steps:

- Clone this repository to your local machine:

Copy code
'''
git clone https://github.com/Yaser-123/Leads-tracker-Chrome-extention.git
'''

- Open Chrome and navigate to chrome://extensions/.

- Enable Developer mode by toggling the switch in the top right corner.

- Click on Load unpacked and select the directory where you cloned this repository.

- The extension should now appear in your list of extensions and is ready to use!

## How to Use
- Save Current Tab URL: Click the "Save Tab" button to save the URL of the current tab.
- Add URL Manually: Enter a URL in the input field and click the "Save Input" button to add it to your list.
- View Saved URLs: All saved URLs will appear in a list. Click any URL to open it in a new tab.
- Clear All URLs: Double-click the "Delete All" button to clear all saved URLs.
## Code Overview
- myLeads: An array that stores all saved URLs.
- inputEl: Reference to the input element where users can manually enter a URL.
- inputBtn: Button that triggers saving the manually entered URL.
- ulEl: Reference to the unordered list element where saved URLs are displayed.
- deleteBtn: Button that clears all saved URLs when double-clicked.
- tabBtn: Button that saves the current tab's URL.
The URLs are stored in the browser's localStorage, so they persist across browser sessions.

## Contributing
- Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements.
