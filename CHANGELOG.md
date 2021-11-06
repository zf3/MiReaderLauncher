
Dev notes by zf3

## 2021-11-6, add DuoKan App (多看桌面) to list of apps
 * com.duokan.einkreader

## 2021-11-6, set-up on M1 mbp
 * MacOS Monterey 12.0.1
 * Android Studio 2020.3.1 Patch 3
 * Command-line SDK and emulator setup:
   1. Download `https://developer.android.com/studio#command-tools` and put it in `$HOME/Library/Android/sdk/cmdline-tools/latest`
   2. Modify `$HOME/.profile` to addd `$HOME/Library/Android/sdk/cmdline-tools/latest/bin` to PATH   
   3. Android Studio -> Preferences -> Appearance & Behavior -> System Settings -> Android SDK -> install SDK for Android 8.1 (Oreo)
   4. **Install emulator for M1**: `sdkmanager --channel=3 emulator`
   5. AVDManager GUI: Create a Nexus 7 VM, with OS image of API>27
```

