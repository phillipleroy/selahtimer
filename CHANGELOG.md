# Changelog

All notable changes to Selah Timer will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] - 2026-02-XX

### 🎉 Initial Release

The first public release of Selah Timer! An elegant timer app designed specifically for timing midweek meeting assignments.

### ✨ Added

#### Core Features
- **Timer System**: Clean countdown timer with start, pause, resume, and stop controls
- **Automatic Start Time Calculation**: App automatically calculates when your assignment begins based on meeting schedule
- **Six Assignment Types**: Support for all standard midweek meeting parts:
  - Treasures from God's Word (10 min default)
  - Spiritual Gems (10 min default)
  - Bible Reading (5 min default)
  - Apply Yourself to Field Ministry (4 min default)
  - Living as Christians (10 min default)
  - Congregation Bible Study (30 min default)
- **Customizable Durations**: Adjust any assignment from 1 to 60 minutes
- **Custom Start Times**: Option to manually set start times if needed

#### Smart Features
- **Late Start Adjustment**: Automatically adjusts remaining time if you start the timer after your scheduled start time
- **Assignment Validation**: Prevents starting timers for assignments that have already passed

#### Live Activities & Dynamic Island
- **Lock Screen Integration**: See your countdown timer without unlocking your device
- **Dynamic Island Support**: Monitor your timer in the status bar area (iPhone 14 Pro and later)
- **Real-time Updates**: Live countdown updates on Lock Screen and Dynamic Island

#### iPad Features
- **Universal App**: Optimized layouts for both iPhone and iPad
- **Split Screen & Slide Over**: Full support for iPad multitasking
- **Adaptive Layout**: Automatically adjusts between portrait and landscape orientations
- **Compact & Regular Size Classes**: Optimized for all screen sizes

#### Design & Accessibility
- **Dark Mode**: Full support with beautiful appearance in both light and dark modes
- **VoiceOver Support**: All controls properly labeled for screen reader users
- **Dynamic Type**: Text scales with system font size preferences
- **High Contrast Support**: Works with increased contrast modes
- **Reduce Motion**: Respects reduced motion accessibility settings

#### Localization
- **English**: Full localization
- **Portuguese**: Full localization

#### Privacy & Security
- **No Data Collection**: Zero personal data collected
- **No Internet Required**: Fully offline functionality
- **Local Storage Only**: All preferences stored securely on device
- **No Tracking**: No analytics or user tracking of any kind

### 🛠️ Technical Details

- Built with SwiftUI for modern, declarative UI
- ActivityKit integration for Live Activities
- WidgetKit foundation for future widget support
- Swift Concurrency (async/await) for timer management
- UserDefaults for local preference storage
- Minimum deployment target: iOS 16.2

---

## [Unreleased]

### Planned Features

Ideas and features being considered for future releases:

- ⌚️ watchOS companion app
- 🎨 Custom themes and color schemes
- 🔔 Haptic feedback options
- 📊 Assignment history tracking
- 🔄 iCloud sync for multiple devices
- 🌍 Additional language localizations (Spanish, French, German, Italian, etc.)
- 📱 Home Screen widgets
- ⏰ Pre-assignment reminders
- 🎯 Custom assignment templates
- 🗓️ Weekly meeting schedule presets

---

## Release Notes Format

For contributors: When adding changes, please use the following categories:

- **Added** - New features
- **Changed** - Changes to existing functionality
- **Deprecated** - Features that will be removed in upcoming releases
- **Removed** - Features that have been removed
- **Fixed** - Bug fixes
- **Security** - Security-related changes

---

## Version History Summary

| Version | Release Date | Highlights |
|---------|--------------|------------|
| 1.0.0   | 2026-02-XX   | Initial release with core timer features, Live Activities, and iPad support |

---

## Links

- [App Store](https://apps.apple.com/app/selah-timer/idXXXXXXXXX)
- [GitHub Repository](https://github.com/yourusername/SelahTimer)
- [Support Documentation](SUPPORT.md)
- [Privacy Policy](PRIVACY.md)

---

**Note**: This changelog is maintained for developers and interested users. Official release notes for the App Store may be formatted differently to comply with App Store guidelines and character limits.
