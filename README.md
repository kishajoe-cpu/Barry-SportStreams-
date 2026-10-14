# Barry SportStreams

Dark, masculine Android TV-style player: embedded video on top, channel list below,
prev/next channel buttons, favorites, search, category chips, and fullscreen landscape.

## Build the APK
1. Install Android Studio (Koala or newer) and open this folder.
2. Let Gradle sync (it will download everything it needs).
3. Debug APK: Build > Build Bundle(s) / APK(s) > Build APK(s).
   File lands in app/build/outputs/apk/debug/app-debug.apk. Copy it to your phone and install.
4. Optional icon: right-click app > New > Image Asset, then add android:icon to the manifest.

## Using it
- Default source is the free iptv-org News playlist.
- Tap the sliders icon (top right) to switch to Sports/Movies/Entertainment or paste any M3U URL.
- Prev/Next buttons step through whatever list is currently showing (search, category, or favorites).
- Tap the video in fullscreen to show/hide controls.

## Customize
- Accent color and theme: Theme.kt (BarryColors).
- Preset playlists: PRESETS list in TvViewModel.kt.
