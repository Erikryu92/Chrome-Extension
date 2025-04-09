# Chrome-Extension
Chrome Extension blocking phishing email.

# Phish Detect
This is a chrome extension to help alert and warn users if they open up a potential phishing email or browses some malicious url.

## Installation
1. Download/clone the repo: 
2. Install the requirements:
```cd phishing-detection && npm install```
3. In chrome, open up the extensions page by going to chrome://extensions
4. Check "Developer mode" then click on "Load unpacked extension". Click the phish_detect folder. This should install the extension. You can disable Developer mode after it is installed.

Note: There may be some startup time before the extension is loaded. Therefore, if you navigate to an email too quickly, the extension may not be loaded and would not detect whether or not the email has failed authentication. Please way a second or two before navigate. Additionally, there is a message in the console that displays when the extension is fully loaded. 
