# UpLink releases

Downloads for [UpLink](https://github.com/Josuath/UpLink), a remote control for your own Windows 11 PC from your Android phone. The source stays in its private repository; this one exists so the installed copies can find their updates without a token.

Every release carries three files:

| File | What it is |
| --- | --- |
| `UpLink.Setup.exe` | The PC side. Installs the service and the agent, or updates an existing install. Asks for administrator rights once. (GitHub does not allow a space in an asset name; once installed it is `UpLink Setup.exe`.) |
| `UpLink.apk` | The Android app, signed with the same key as every previous release, so it installs over the one you have. |
| `SHA256SUMS` | The SHA-256 of the two files above. The updaters built into UpLink verify a download against it before running anything. |

You rarely need this page: the tray icon on the PC (**Check for update…**) and the app's Settings screen fetch the latest release from here, verify it and hand it to the installer.
