<div align="center">
<h3>OneComme - Template Utils</h3>
<p>This is OneComme Plugin Repo - A comprehensive plugin tool for creating and managing various widgets and donation overlays for streaming platforms.</p>
<p>
  <a href="README.md">English</a> | 
  <a href="README-zh-CN.md">简体</a> | 
  <a href="README-zh-TW.md">繁體</a> | 
  <a href="README-JP.md">日本語</a>
</p>
</div>



# OneComme-TemplatePlugin

## Overview

OneComme-TemplatePlugin is an independent plugin interface for running OneComme plugins, providing template management, real-time preview, and customization features for streamers across multiple platforms including YouTube, Twitch, and Bilibili.

## Features

- **Widget Functionality**: Create various widgets using OneComme's template management system
- **Multi-Platform Support**: Compatible with YouTube, Twitch, and Bilibili
- **Real-Time Preview**: UI interface with template adjustment and real-time preview
- **Template Management**: Preset management, adjustment, saving, and personalization features
- **Donation Progress Overlay**: Gank platform donation progress bar with customizable features
- **Multi-Language Support**: Available in English, Japanese, Simplified Chinese, and Traditional Chinese
- **Time Zone Customization**: Configurable time zones for overseas use or VPN scenarios
- **Comment Filtering**: Advanced filtering capabilities for different message types

## ▶Description◀
Template Utils is a plugin designed to enhance the comment display effects of OneComme.
In the new version 3.0, more convenient and intuitive functional modules have been added to customize OneComme templates. Equipped with a UI interface, preset management, and comment filtering, it allows streamers to easily create their own unique comment style without the hassle of dealing with code adjustments.

**🔧 Comment Data Refinement**
Optimizes and refines OneComme's comment data, enhancing details for more diverse display effects.

**🎨 UI Visual Adjustment Interface**
With the user interface, streamers can easily customize template presets without any coding knowledge. From styles to management features, everything is under your control.

**👀 Real-Time Preview Feature**
Instantly view the effects of adjustments as you make them, meeting the needs of various streaming scenarios.

**🔗 One-Click Preset Link Generation**
Generate a dedicated link for each template preset. Simply copy and paste the link for quick and seamless application to your stream.

**🌍 Multilingual Support**
Supports English, Japanese, Simplified Chinese, and Traditional Chinese, catering to the language needs of a wide range of streamers.

**⚙️ Custom Comment Filtering Feature**
Filter comments based on keywords or rules to avoid sensitive content that could disrupt your streaming environment, ensuring a safer and more flexible streaming experience.

**🔗 OneComme**
A comment app for streamers
https://onecomme.com/

**🔗 Support**
For inquiries, please send a DM on X/Twitter.
https://x.com/soma_desune

**🔗 Usage Permission**
● Feel free to use it for streaming, VTuber activities, etc.
● Adjust freely to match your own style.

## ▶ Plugin Installation Guide ◀
The functionality check was performed on OneComme v7.2, so if it doesn't work, please try upgrading to v7.2 or higher.

**💡 Tip:**
If you are already using a previous version of Template Utils or a template, please manually delete the old version and update to the latest 3.0 version! We are planning to release many more new templates and features in the future, so stay tuned!

Steps to Delete Old Version Plugin:
https://youtu.be/acPHE-oCppI

Steps to Install New Plugin:
https://youtu.be/op3T9gfpBw4

How to Use the Plugin:
https://youtu.be/JlSo1dYGf_w


## ▶ Template Installation Guide ◀
Please refer to the official OneComme installation guide for templates.
https://onecomme.com/docs/feature/templates

Steps to Delete Old Version Template:
https://youtu.be/zjVyK6Gh2CA

Steps to Install New Template:
https://youtu.be/9cNlF6AbJ_8


## ▶ Usage ◀

1. Open OneComme
2. Load the plugin through the template management system
3. Configure your preferred settings in the UI interface
4. Customize templates and widgets as needed
5. Enable real-time preview to see changes instantly

# Update Log

### Version 3.0.0 July 12, 2025

Description:

Major overhaul of data storage structure, with the addition of "Greeting" statistics and concurrent viewer count display.

New Features:

1. "Greeting" statistics function: Tracks visitor comments based on keywords, such as counting greetings and courtesies.
2. "First-time viewer" statistics function: Compiles statistics based on new viewers collected by OneComme.
3. Concurrent viewer count display: Shows data from OneComme for different platforms, including: online concurrent viewers, "like" counts.
4. Added new adjustable properties.
5. Added Socket communication functionality.

Modified Features:

1. Modified preset saving method, original presets can now be used without importing.
2. Only custom presets are now saved to state.json.
3. Time-widget has been renamed to template-time, with modified time format and presentation modes.
4. Removed preset import function from settings.
5. Removed Gank ID setting from settings, now saved directly in frontend templates.
6. Simplified timezone adjustment settings.
7. Fixed known bugs.

### Version 2.1.0 March 14, 2025

Description:

Official release on Booth and Gank Shop

Integration of Widgets and Gank Donation Progress Overlay

New Features:

1. Widget functionality, utilizing OneComme's template management system to create various widgets.
2. Gank platform donation progress bar: Extended customizable features using Gank's data interface, enabling future expansion for various template formats.
3. Time zones: With upcoming templates and widgets displaying time, considering scenarios of overseas use or VPN affecting time zones, added customizable time zone settings.
4. Time format languages: Customized for different language regions, available in English, Japanese, Simplified Chinese, and Traditional Chinese.

Modified Features:

1. Modified template preset file properties, added .html file indexing.

Bug Fixes:

1. Fixed known bugs

### Version 2.0.0 February 06, 2025

Description:

Official release on Booth

Providing independent interface for running OneComme plugin. Comprehensive upgrade to a more concrete plugin tool

New Features:

1. UI interface, template adjustment real-time preview interface.
2. Template preset management, adjustment, saving, and other personalization features.
3. Converting CSS to JSON with Vue.js CSS preset implementation.
4. Using OneComme's electron-store module for user data storage.
5. Interface languages: Available in English, Japanese, Simplified and Traditional Chinese, with user-customizable switching.
6. Integration of original filtering features into user settings.
7. Preset link functionality.

### Version 1.1.0 December 14, 2024

Description:

Released alongside CleanFlow template on Booth and Gank Shop

[OneComme Template] CleanFlow Danmaku Style [Comment Frame]

Bug Fixes:

1. Bilibili original data model changes, display data reorganization

### Version 1.0.0 October 26, 2024

Description:

Released alongside Integration template on Booth and Gank Shop

[OneComme Template] Integration Black & White Preset Danmaku Style [Comment Frame]

Features:

1. Comment filtering
2. YouTube, Twitch, Bilibili platform donation message attribute categorization.
3. Bilibili comment data type reorganization.

## License

See [LICENSE](LICENSE) for more information.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
