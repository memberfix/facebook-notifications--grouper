# Facebook Notifications Grouper

A Chrome extension that organizes Facebook notifications by their originating page or group, making it easier to batch-process your social media interactions.

![Extension Screenshot](https://memberfix.rocks/wp-content/uploads/2025/03/notifications-panel.png)

![Extension Screenshot](https://memberfix.rocks/wp-content/uploads/2025/03/all-notifications-screen.png)

## Features

- Automatically groups notifications by their source (page or group)
- Collapsible sections for each group
- Simple toggle to enable/disable automatic grouping
- Refresh button to manually regroup notifications
- Works with both the notifications page and the notifications popup

## Why This Extension?

Facebook's default notification system displays all notifications in strict chronological order, which can make it difficult to address related notifications from the same group or page. This extension solves that problem by organizing your notifications by their source, allowing you to handle similar interactions together.

## Installation

### From Source (Developer Mode)

1. Download or clone this repository to your computer
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" using the toggle in the top-right corner
4. Click "Load unpacked" and select the folder containing the extension files
5. The extension should now appear in your extensions list and be ready to use

### From Chrome Web Store

*Coming soon*

## Usage

1. After installation, click on the Facebook notifications icon or go to the notifications page
2. Your notifications will automatically be grouped by their source (page or group)
3. Click on the extension icon in the toolbar to:
   - Toggle automatic grouping on/off
   - Manually refresh the grouping

## How It Works

The extension scans the notifications in Facebook's interface, identifies which group or page each notification originated from, and then reorganizes them into collapsible sections while preserving all the original functionality.

## Compatibility

- Works with Chrome 88+
- Tested on Facebook's current interface (as of 2025)
- May require updates when Facebook changes its interface

## Privacy

This extension:
- Does NOT collect any data
- Does NOT send any information to external servers
- Only reads and modifies the Facebook notifications interface locally
- Requires only the minimum permissions needed to function

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This extension was created to improve my own Facebook notification management workflow
- Thanks to the open-source community for providing excellent documentation and examples

## Future Plans

- Add options to customize the appearance
- Add ability to filter notifications by keywords
- Add notification count badges for each group

---

*This extension is not affiliated with, endorsed, or sponsored by Facebook.*
