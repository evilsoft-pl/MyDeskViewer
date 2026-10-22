# MyDeskViewer — October 2026 Update

This release brings major usability and reliability improvements since **v2026.9.20.1823**, including standalone file transfer, more flexible remote access, refreshed session controls, and significant Windows and Android refinements.

## Highlights

- **Standalone File Transfer (Windows and Android):** Start a file-only connection directly from a saved computer's options menu, without first opening its remote desktop. Existing access-password or local-approval requirements still apply; remote activity is identified as file transfer. Screen capture and video traffic are avoided when they are not needed.
- **Guest remote access (Windows):** Connect with a Machine ID and access password without signing in to a MyDeskViewer account. Guest sessions use the secure relay and are limited to one session at a time and five minutes per session; text clipboard is supported, while file and image clipboard transfers are restricted in guest mode.
- **More consistent appearance (Windows):** Light, Dark and Automatic themes, with improved readability across navigation, Settings, dialogs and remote-session tools.
- **Smoother connections:** Refined direct P2P handling, remote-session responsiveness, image-quality adjustment and recovery after interruptions.
- **Refreshed Android experience:** Clearer connection feedback, a redesigned remote-session toolbar and improved layouts on modern phones.

## Windows desktop

### Remote sessions and device management

- Improved peer-to-peer connection handling, session status, automatic quality indications and capture recovery.
- Added convenient entry points for chat directly from the computer list.
- Improved chat message notifications, previews and navigation to conversations.
- Expanded QR-code sharing/import and convenient options for copying and saving access information.
- Improved Peers/Favorites navigation, remembered filters and saved-computer group editing, including offline computers.
- Added tray controls for managing automatic startup without interrupting the current connection.
- Improved remote-session window naming and transport details, including P2P or relay information.
- Refined background operation, disconnect handling, tray cleanup and update/shutdown behavior.

### File Transfer and access

- Added **File transfer** to the desktop computer context menu, reusing the existing file explorer and authentication mechanisms.
- Added lightweight Sender support for file-only sessions without changing standard desktop capture, input or P2P operation.
- Preserved the existing **Allow / Cancel** prompt whenever local approval is required.
- Improved file-transfer panel closing and session cleanup.

### Chat, clipboard and privacy

- Improved native Windows clipboard interoperability and stability.
- Updated the Windows viewer chat editor to use the native Windows text input, enabling the system **Win + .** emoji picker and reliable caret/focus handling.
- Kept full-color emoji in chat history; **Enter** sends a message and **Shift + Enter** inserts a line break.
- Prevented chat keystrokes from being forwarded to the remote desktop while typing.
- Improved the privacy **Cover** overlay with DPI-aware positioning and native click-through behavior, while maintaining remote input support.
- Refined the Cover button's active-state feedback.

## Android

- Refreshed the session toolbar with compact icons for Keyboard, Refresh, Copy, Enter text, Files and Tools.
- Improved portrait/landscape layouts and spacing around Android status/navigation bars.
- Added more visible **Connecting** feedback to help prevent accidental repeated connection attempts.
- Improved session rendering responsiveness and recovery when switching apps or returning from a call.
- Refined quality controls, connection status and optional technical details.
- Added standalone File Transfer access from the computer menu, with the existing access controls.
- Improved the File Transfer panel's Light/Dark system appearance, with Access and Refresh icons.
- Simplified computer-list actions and navigation, including Add, Refresh, Scan QR, Access and Settings.

## macOS

- Refreshed the main interface with a Windows-style Peers layout.
- Improved navigation spacing for Peers, Favorites and Settings.
- Added expanded peer management with Add/Edit and per-computer options.
- Added dedicated Access and Settings views and improved group management.

## Stability and compatibility

- Improved overall remote-session reliability, automatic image-quality adjustment and recovery after network or display interruptions.
- Refined application and service update handling, including shutdown behavior and release/build compatibility.
- Continued interface and language refinements across supported platforms.

## Installation and downloads

Select the appropriate package from **Assets** once the release binaries have been attached. Available downloads vary by platform and distribution channel. For official downloads and more information, visit [mydeskviewer.com](https://mydeskviewer.com/).

Do not replace an installed version with an older build. Windows packages may use different deployment formats (desktop installer, MSI, or Offline installer); choose the package intended for your environment.

## Feedback

Please report reproducible bugs through [GitHub Issues](https://github.com/evilsoft-pl/MyDeskViewer/issues) and share ideas in [GitHub Discussions](https://github.com/evilsoft-pl/MyDeskViewer/discussions). Do not include passwords, access tokens or other sensitive information in public reports.

---

Developed and published by **evilsoft**.