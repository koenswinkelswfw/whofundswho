# WhoFundsWho

WhoFundsWho is a browser extension that instantly shows you who funds the experts, politicians, think tanks, and other institutions you are reading about.

## Table of Contents

- [Installation](#installation)
  - [Via Chrome Web Store](#via-chrome-web-store)
  - [Manual Installation](#manual-installation)
- [Usage](#usage)
- [Uninstallation](#uninstallation)
- [Mobile Support](#mobile-support)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
 
## Installation

### Via Chrome Web Store

1. **Open the Chrome Web Store:**
   - Navigate to the [Chrome Web Store](https://chrome.google.com/webstore).

2. **Search for WhoFundsWho:**
   - In the search bar, type "WhoFundsWho" and press Enter.
   - Or navigate to WhoFundsWho's [page](https://chromewebstore.google.com/detail/whofundswho/pfdecgjliclkncfaiciljlphfenigmno) in the Web Store directly.

3. **Add the Extension to Chrome:**
   - Click on the **"Add to Chrome"** button next to the WhoFundsWho extension.
   - Confirm the installation by clicking **"Add extension"** in the prompt.

### Manual Installation

If you prefer not to use the Chrome Web Store, follow these steps to manually install the extension:

1. **Download the Extension:**
   - In the repository click on the `whofundswho.zip` file.
   - Then click on the horizontal triple dots in the top right corner of the file view.
   - Select **"Download"** to download the ZIP file.

2. **Extract the ZIP File:**
   - Locate the downloaded `whofundswho.zip` file on your computer.
   - Right-click the ZIP file and select **"Extract All..."** or use your preferred extraction tool.
   - This will create a folder named `dist`.

3. **Open Chrome's Extension Manager:**
   - In Chrome, navigate to `chrome://extensions/` by typing it into the address bar and pressing Enter, or by navigating to it in the browser's menu.

4. **Enable Developer Mode:**
   - In the top right corner of the Extensions page, toggle the **"Developer mode"** switch to the **"On"** position.

5. **Load the Unpacked Extension:**
   - Click on the **"Load unpacked"** button.
   - In the file chooser dialog, navigate to the location of the extracted `dist` folder.
   - Select the `dist` folder and click **"Select Folder"**.

6. **Enable the Extension:**
   - After loading, ensure that the WhoFundsWho extension is enabled. If not, toggle the switch next to it.

7. **Configure the Extension:**
   - Upon installation, the Options page will open automatically.
   - Choose your preferred settings as described on the Options page itself.

## Usage

Once installed and enabled, WhoFundsWho will automatically display funding information for experts, politicians, think tanks, and other institutions on the webpages you visit. You can customize the display settings through the Options page to suit your preferences.

## Uninstallation

To remove the WhoFundsWho extension from your browser:

1. **Open Chrome's Extension Manager:**
   - Navigate to `chrome://extensions/` in Chrome.

2. **Locate WhoFundsWho:**
   - Scroll through the list of installed extensions to find **WhoFundsWho**.

3. **Remove the Extension:**
   - Click the **"Remove"** button associated with WhoFundsWho.
   - Confirm the removal by clicking **"Remove"** again in the prompt.

## Mobile Support

### Android

*WhoFundsWho* is a browser extension, and most mobile browsers do not support extensions or only support a select few. But there are some exceptions.

Until January 2025 the best option was the Kiwi browser, but it has now been [discontinued](https://github.com/kiwibrowser/src.next). The good news is that its extension functionality code has now been integrated into the [Microsoft Edge Canary](https://play.google.com/store/apps/details?id=com.microsoft.emmx.canary&hl=en_CA) browser.

At this point the mobile version of the *Edge Canary* browser only allows for a select few extensions to be installed directly via the [Microsoft Edge Add-ons store](https://microsoftedge.microsoft.com/addons/Microsoft-Edge-Extensions-Home). But if you are willing to use that browser's 'developer mode' you can manually install both *Microsoft Edge* add-ons (i.e. extensions) and *Chrome* extensions in the mobile browser.

Note that using developer mode does mean that the installation process bypasses some of the browser's built-in security checks. So you should only use it to install trusted extensions.

If for this or other reasons you are not comfortable installing *WhoFundsWho* using the `.crx` file, note that from the last week of February *WhoFundsWho* should also be available in the *Microsoft Edge Add-ons* store. This means that Microsoft will have verified it as a valid extension. You will then be able to install *WhoFundsWho* in the mobile *Edge Canary* browser using its store ID.

If you *are* comfortable installing using the `.crx` file, then here is how to do it:

- On your Android device, download the [whofundswho.crx](https://github.com/koenswinkelswfw/whofundswho/blob/main/whofundswho.crx) extension file from our [Github page](https://github.com/koenswinkelswfw/whofundswho/tree/main).
- Download the *Edge Canary* browser from the [Google Play Store](https://play.google.com/store/apps/details?id=com.microsoft.emmx.canary&hl=en_CA) and install it.
- Open **"Edge Canary"** and go to **"Settings"** => **"About Microsoft Edge"**.
- Tap the **"Edge build number"** (e.g., `xx.0.2487.0`) 5 times to enable **"Developer Options"**.
- Go back to the **"Settings"**, and scroll down until you see **"Developer Options"**.
- Scroll down until you see the **"Extension install by crx"** option and select it.
- Tap on **"Choose .crx file"** and navigate to where you have saved the downloaded `whofundswho.crx` file, and select it.
- This will install *WhoFundsWho* and open its start screen and then the user menu.
- After *WhoFundsWho* has automatically downloaded keywords data and finished its setup, which may take 30-60 seconds, it will automatically run in the browser.
