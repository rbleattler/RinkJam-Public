# RinkJam

### Bring the Hype to Game Day

RinkJam turns your iPhone into a powerful, customizable soundboard for sports events. Trigger music clips, goal horns, hype effects, intros, and more from one simple interface built for live game action.

Whether you're a coach, parent, or arena DJ, RinkJam helps you create an electric atmosphere your players and fans will love.

---

## What Is RinkJam?

RinkJam is a free native iOS app that lets anyone run a professional-style game-day soundboard right from their phone. It’s designed primarily for hockey, but works great for any sport or event that needs crowd energy and quick-trigger audio.

Under the hood, RinkJam is a SwiftUI app that uses AVFoundation and MusicKit to:

- Play local audio clips stored on device
- Integrate with Apple Music (when configured)
- Let you record, trim, and tag your own clips for live playback

This repository is the public landing page and issue tracker for the RinkJam app. The app’s source code lives in a separate private repository.

---

## Key Features

- **Custom Tags for Every Moment**  
  Organize your sounds by tags such as `#Goal`, `#Intro`, `#Warmup`, or `#Penalty` for quick playback during live events. Tags are auto-discovered from your clips and can be customized (colors, visibility, order).

- **Flexible Audio Clips**  
  Create clips from local audio or Apple Music content. Set **start** and **end** points so only the best part of each track is played.

- **Quick Soundboard Interface**  
  The main soundboard view shows tag groups and buttons optimized for fast, on-the-fly triggering during games.

- **Hot Mic Mode**  
  Use your device like a rink-side microphone for announcements. Choose between push-to-talk and toggle modes.

- **Now Playing Panel**  
  Always see what’s currently playing and stop it instantly when needed.

- **Audio Recording**  
  Record new audio clips directly in the app and add them to your libraries.

- **Offline Ready**  
  Your libraries, clips, and tags are stored on your device. RinkJam can run completely offline for venues with poor or no connectivity.

- **Privacy by Design**  
  RinkJam stores your data locally on your device. There are no accounts, ads, or tracking built into the app.

> Some advanced features—like Apple Music playback—require additional setup as described in the in-app documentation and developer documentation for MusicKit.

---

## Download

RinkJam is available on the **App Store** for iPhone.

[View on the App Store](https://apps.apple.com/)  
*(Replace this link with the live App Store URL once available.)*

---

## Screenshots

_Add screenshots here once they’re ready._

For example:

- Main soundboard view with tags
- Clip editor with waveform + range slider
- Library / clip management views
- Hot Mic mode

```markdown
![Soundboard](screenshots/soundboard.png)
![Clip Editor](screenshots/clip-editor.png)
![Hot Mic](screenshots/hot-mic.png)
```

---

## How It Works (High-Level)

RinkJam is built using:

- **Swift + SwiftUI** for the UI
- **ObservableObject** services for state and data flow:
  - Audio playback (local and Apple Music)
  - Clip metadata and user-created clips
  - Tags and settings
  - Audio recording
- **AVFoundation** for local audio playback and recording
- **MusicKit** (when configured) for Apple Music playback

Data such as user-created clips, tag customizations, and settings are stored locally on-device (e.g., via `UserDefaults`), so your setup persists between sessions.

---

## Support, Feedback, and Issues

Use this repository to:

- Report bugs
- Request features
- Ask questions
- Share ideas and feedback

Before opening a new issue:

1. Check existing issues to see if your topic is already covered.
2. Use the appropriate issue template (bug report, feature request, or question).
3. Provide as much detail as possible (device, iOS version, steps to reproduce, etc.).

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

---

## Privacy

RinkJam is designed to minimize data collection and prioritize user privacy.  
For details, see the [Privacy Policy](PRIVACY.md).

---

## About the Project

RinkJam is built in Swift and powered by Apple’s native frameworks, including AVFoundation and MusicKit.  
It is designed and developed by **Coast Technologies LLC**, an independent software and cloud services company.

Visit [coasttech.io](https://coasttech.io) to learn more.

---

## License

RinkJam is a closed-source application. This repository serves as a public landing page and issue tracker for feedback, ideas, and feature requests.

See [LICENSE](LICENSE) for details.

---

## Connect

- [Official Website](https://coast-technologies.com)
- [Email](mailto:contact@coast-technologies.com)

---

© 2025 Coast Technologies LLC. All rights reserved.
