## Focus Filter Browser Extension

A minimal browser extension to help you stay focused and productive by managing digital distractions. Block distracting websites, track your focus sessions, and build better work habits.

![Focus Filter](icons/icon128.png)

## 🪂 Features

### Core Functionality
- **Website Blocking**: Automatically block distracting sites during focus sessions
- **Focus Timer**: Built-in Pomodoro-style timer (customizable duration)
- **Statistics Tracking**: Monitor your daily focus time and completed sessions
- **Instant Blocking**: Immediate activation when focus mode is enabled

### User Experience
- **Clean Interface**: Minimalist design with essential controls
- **Quick Access**: One-click to start/stop focus sessions
- **Visual Feedback**: Clear timer display and session status
- **Customizable Settings**: Flexible configuration options

## 📦 Installation

### For Users
1. Download the extension (Chrome Web Store link coming soon)
2. Click "Add to Chrome"
3. Configure your blocked sites list in the settings

### For Developers
1. Clone the repository:
```bash
git clone https://github.com/aquaticcalf/focus-filter.git
cd focus-filter
```

2. Load the extension in Chrome:
- Open Chrome and navigate to `chrome://extensions/`
- Enable "Developer mode" in the top right
- Click "Load unpacked"
- Select the extension directory

## 🔧 Usage

### Quick Start
1. Click the Focus Filter icon in your browser toolbar
2. Click "Start Focus Session"
3. The timer will begin and blocked sites will be inaccessible
4. Works until the timer ends or manually stop the session

### Customizing Settings
1. Click the "Settings" button in the popup
2. Add or remove sites from your blocked list
3. Adjust session duration
4. Save your changes

## 🏗️ Project Structure

```
focus-filter/
├── manifest.json        # Extension configuration
├── popup/
│   ├── popup.html      # Main popup interface
│   └── popup.js        # Popup functionality
├── background/
│   └── background.js   # Background service worker
├── options/
│   ├── options.html    # Settings page
│   └── options.js      # Settings functionality
└── blocked/
    └── blocked.html    # Blocked site page
```

## 🛠️ Development

### Prerequisites
- Google Chrome or Chromium-based browser
- Basic knowledge of HTML, CSS, and JavaScript
- Text editor or IDE

### Development Flow
1. Make changes to the source files
2. Reload the extension in Chrome
3. Test functionality
4. Repeat as needed

### Key Files
- `manifest.json`: Extension configuration and permissions
- `popup.js`: Main extension functionality
- `background.js`: Background processes and site blocking
- `options.js`: Settings management

## 🔒 Privacy

Focus Filter respects your privacy:
- No data collection
- All data stored locally
- No external services
- No analytics or tracking

## ⚡ Performance

The extension is designed to be lightweight:
- Minimal resource usage
- Efficient site blocking
- No continuous background processes
- Small storage footprint

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch
```bash
git checkout -b feature/amazingfeature
```
3. Commit your changes
```bash
git commit -m 'Add some amazingfeature'
```
4. Push to the branch
```bash
git push origin feature/amazingfeature
```
5. Open a Pull Request

## 📝 Planned Features

- [ ] Advanced statistics and insights
- [ ] Custom blocking schedules
- [ ] Site categorization
- [ ] Break reminders
- [ ] Progress streaks
- [ ] Export/import settings
- [ ] Multiple blocking profiles
- [ ] Website visit analytics

<!-- ## 🐛 Known Issues -->

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Support

For support:
- Open an issue
- Email: [aquaticcalf@proton.me](mailto:aquaticcalf@proton.me)
- Documentation: [Wiki](https://github.com/aquaticcalf/focus-filter/wiki)

## 🙏 Acknowledgments

- Icons by [Octicons Icons](https://primer.style/foundations/icons/)
- Inspired by the Pomodoro Technique
- Built with vanilla JavaScript
---