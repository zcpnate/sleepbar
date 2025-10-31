# Changelog

All notable changes to SleepBar will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] - Coming Soon

### 🎉 Initial Release

#### Added
- Quick timer presets (15, 30, 60, 120 minutes)
- Custom duration timer with hours and minutes
- Schedule sleep at a specific time
- Choose between system sleep or display-only sleep
- Pre-sleep warning notification (1 minute before timer expires)
- Option to cancel or snooze timer from warning popup
- Beautiful liquid glass design following Apple's guidelines
- Menu bar integration with active timer display
- Automatic updates via Sparkle framework
- 7-day free trial
- License activation via Lemon Squeezy

---

## Future Releases

Have a feature request? [Open an issue](https://github.com/zcpnate/sleepbar/issues) or email [nate@sleepbar.app](mailto:nate@sleepbar.app)!

### Ideas for Future Versions
- [ ] Customizable warning time (not just 1 minute)
- [ ] Multiple timer profiles/presets
- [ ] Keyboard shortcuts
- [ ] Sound alerts (in addition to visual warning)
- [ ] Statistics (track sleep timer usage)
- [ ] Dark mode icon option

---

## How to Update This Changelog

When releasing a new version:

1. **Add a new section** for the version:
```markdown
## [X.Y.Z] - YYYY-MM-DD

### Added
- New feature 1
- New feature 2

### Fixed
- Bug fix 1
- Bug fix 2

### Changed
- Changed behavior 1
```

2. **Update the website** (`index.html`):
   - Copy the new version entry to the changelog section
   - Move previous versions down

3. **Commit and push**:
```bash
git add CHANGELOG.md index.html
git commit -m "Release v X.Y.Z"
git push
```

---

[1.0.0]: https://github.com/zcpnate/sleepbar/releases/tag/v1.0.0

