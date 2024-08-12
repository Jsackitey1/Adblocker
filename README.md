### Sackitey Adblocker

This project is a custom-built Adblocker Chrome extension designed to block unwanted advertisements across various websites. The extension filters out ads using a predefined list of ad-serving domains, enhancing user browsing experience by preventing intrusive ads from loading.

#### Features:
- **Customizable Ad Blocking**: Blocks ads from a wide range of popular ad networks, including Google AdSense, DoubleClick, Facebook Ads, and more.
- **Real-Time Blocking**: Utilizes Chrome's `declarativeNetRequest` API to block requests to ad-serving domains in real-time.
- **Lightweight and Efficient**: Built with performance in mind, the extension runs smoothly without affecting the browsing speed or consuming excessive resources.

#### Technologies Used:
- **JavaScript**: Core logic for handling ad-blocking rules.
- **Manifest V3**: Modern Chrome extension architecture with service workers.

#### How It Works:
1. The extension listens for network requests made by your browser.
2. Requests matching the patterns defined in the filter list are blocked before they can load.
3. Users can enjoy a cleaner, ad-free browsing experience.

#### Installation:
- Clone the repository.
- Load the extension in Chrome by enabling developer mode and selecting the `Load unpacked` option.
- Enjoy ad-free browsing with the Sackitey Adblocker!

