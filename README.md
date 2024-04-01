# Website Blocker Chrome Extension

This Chrome extension allows you to block access to specific websites by replacing their content with a customizable message.

## How to Use

1. **Installation**:
   - Clone or download this repository to your local machine.

2. **Load Extension**:
   - Open Chrome browser.
   - Go to `chrome://extensions/`.
   - Enable "Developer mode" by toggling the switch in the top right corner.
   - Click on "Load unpacked" and select the directory where you've cloned/downloaded this repository.

3. **Customize Blocked Websites**:
   - Open the `content.js` file in the `extension` directory.
   - Update the `blockedWebsites` array with the URLs of the websites you want to block.

4. **Test**:
   - Visit one of the blocked websites to see the extension in action.
   - The content of the blocked website will be replaced with a message indicating that the website is blocked.

5. **Customization**:
   - You can customize the message displayed when a website is blocked by modifying the `generateHTML` function in the `content.js` file.
   - Additionally, you can customize the styles of the blocked message by modifying the `generateSTYLES` function.

## What it Does

- When activated, the extension checks if the current website matches any of the URLs in the `blockedWebsites` array.
- If a match is found, it replaces the content of the webpage with a customizable message indicating that the website is blocked.
- Users can customize the list of blocked websites and the message displayed for blocked websites by editing the `content.js` file.


