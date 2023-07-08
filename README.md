
# Website Blocker

The Website Blocker is a browser extension designed to block access to specific websites. It prevents users from accessing popular social media platforms and streaming services by replacing the content of the blocked pages with a custom message.

## Features

- Blocks access to selected websites, such as YouTube, Facebook, Instagram, Discord, Snapchat, WhatsApp, Telegram, Netflix, and Hotstar.
- Displays a customized error page with a message indicating that the page cannot be accessed.
- Uses animations and graphics to enhance the visual appeal of the error page.

## Installation

To install the Website Blocker browser extension, follow these steps:

1. Download the extension files or clone the repository.
2. Open your browser and go to the extension settings.
3. Enable developer mode or similar option.
4. Choose "Load unpacked" or "Load extension" and select the folder containing the extension files.
5. The extension should be successfully installed and activated.

## Usage

Once the Website Blocker extension is installed and active, it will block access to the specified websites automatically. When a blocked website is visited, the extension will display a customized error page instead of the original content.

The error page includes a message indicating that the page cannot be accessed and encourages users to focus on their studies or work. The page also contains animated graphics, such as a bookshelf with doors, to enhance the visual experience.

## Configuration

The list of blocked websites can be modified by editing the `content.js` file. To add or remove blocked websites, you need to modify the `switch` statement in the code and specify the desired website hostname.

For example, to block access to Twitter, you can add the following case to the `switch` statement:

```javascript
case "www.twitter.com":
    alert("Denied ACCESS with IRON FISTS");
    document.body.innerHTML = getpage();
    break;
```

Similarly, you can add or remove cases for other websites as needed.

## Compatibility

The Website Blocker extension is compatible with modern web browsers that support the Manifest V3 specification, such as Google Chrome.

## License

The Website Blocker extension is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to modify and distribute the extension in accordance with the terms of the license.

