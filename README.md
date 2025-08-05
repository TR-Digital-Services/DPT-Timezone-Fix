# DPT Timezone Fix

A robust solution for the [Daily Prayer Time for Mosques](https://wordpress.org/plugins/daily-prayer-time-for-mosques/) WordPress plugin that resolves timezone-related display issues and ensures accurate prayer time calculations.

## 🙏 Credit

This plugin was developed to enhance the functionality of the excellent [Daily Prayer Time for Mosques](https://wordpress.org/plugins/daily-prayer-time-for-mosques/) plugin, created by [mmrs151](http://mmrs151.wordpress.com).

## 🚀 Features

- **Automatic Timezone Detection**: Seamlessly handles timezone settings between WordPress and the Daily Prayer Time plugin
- **Non-Intrusive Fix**: Works alongside the original plugin without modifying core files
- **Error-Resistant**: Comprehensive error handling and fallback mechanisms
- **Lightweight**: Minimal performance impact on your website
- **Admin Notifications**: Informs you if the Daily Prayer Time plugin is not active

## 🛠️ Problem Solved

Fixes the "Uncaught TypeError: Cannot read properties of null (reading 'value')" error that prevents the prayer times table from displaying correctly. This occurs when the timezone offset element is missing from the page.

## 🔧 Installation

1. Download the latest release from the [Releases](https://github.com/TR-Digital-Services/DPT-Timezone-Fix/releases) page
2. Upload the ZIP file to your WordPress site (Plugins → Add New → Upload Plugin)
3. Activate the plugin
4. That's it! The fix will work automatically

## 🧪 Compatibility

- WordPress 5.0+
- [Daily Prayer Time for Mosques](https://wordpress.org/plugins/daily-prayer-time-for-mosques/) plugin (tested with version 2025.07.15)
- PHP 7.4+
- All modern browsers

## 📝 Usage

No configuration needed! The plugin works automatically once activated. It will:

1. Add the missing timezone offset element
2. Ensure proper initialization of the prayer times display
3. Handle timezone conversions correctly

## 🔍 Debugging

If you encounter any issues:

1. Open your browser's developer console (F12)
2. Look for messages starting with "DPT Timezone Fix"
3. These messages will help identify any problems

## 👨‍💻 Author

**Arnel G.**  
🌐 [arnelbg.com](https://arnelbg.com/)

## 🤝 Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md) before submitting pull requests.

## 📜 License

GPL-2.0-or-later © 2025

---

*This plugin is not affiliated with or endorsed by the original Daily Prayer Time for Mosques plugin developers.*
