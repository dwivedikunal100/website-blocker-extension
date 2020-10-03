# website-blocker-extension
An open source chrome extension to block websites for digital decluttering


## How to use the extension

1. Clone the repository
2. Open the Extension Management page by navigating to chrome://extensions.
[The Extension Management page can also be opened by clicking on the Chrome menu, hovering over More Tools then selecting Extensions.]

3. Enable Developer Mode by clicking the toggle switch next to Developer mode.
4. Click the LOAD UNPACKED button and select the "website-blocker-extension" folder.

> Currently the only sites blocked are facebook and instagram.

To add/remove blocked URLS, go to background.js files and 
modify
`{ urls: ["*://www.instagram.com/*", "*://www.facebook.com/*"] }`  as per the need.