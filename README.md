# Frequency Meditation

Android app for generating and playing binaural beats using user-defined stereo sine waves.

## Features

- Input left/right frequencies in Hz
- Set playback duration in seconds
- Audio generated using `AudioTrack` in stereo
- Media-style notifications for play/pause control
- Built with Jetpack Compose
- Auto-checks for latest GitHub release version

## Usage

1. Enter left and right ear frequencies (Hz)
2. Enter playback duration (seconds)
3. Tap "Play" to begin binaural playback
4. Use notification to pause/resume

## Permissions

- `POST_NOTIFICATIONS` — Required to display media-style playback control notifications and update notifications.
- `INTERNET` — Required for checking the latest GitHub release version online.
- `REQUEST_INSTALL_PACKAGES` — Required to allow installing updates from APK files downloaded by the app.


## Requirements

- Android 14.0 (API 34) or higher

## Build

Open in Android Studio or build via Gradle:

```bash
./gradlew assembleDebug
