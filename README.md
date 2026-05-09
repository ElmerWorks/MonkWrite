# MonkWrite - User Instructions

MonkWrite is a distraction-free writing environment for Android phones and tablets. It is designed for fast, keyboard-driven writing with a focus on stability and simplicity. MonkWrite requires a keyboard, optimally a Bluetooth Keyboard. I developed and tested it on a Keychron B1 Pro.

Installation : MonkWritev0.1-debug.apk is an Android app package produced by Android Studio. It is intended for beta test purposes for eventual uploading to the Google Play Store. After downloading the app to your device you can select it and the launch will start. At that point Android will warn you about unsafe apps and if you want to proceed. Grant permission (you may to allow in Settings) and it should install. I tested it on a Lenovo Tab One (2025), a Samsung S24 (2024), A Moto G (2022). It failed to launch on a Samsung Galaxy Tab A (2019). If you have an older Android installed on your device it may not run. I may take a look at this in future revs.

## Key Features

- **8 Independent Buffers**: Work on multiple drafts simultaneously.
- **Persistent Storage**: Your text and margin settings are automatically saved when you switch buffers or leave the app.
- **Immersive Mode**: Full-screen writing with no system distractions.
- **Hardware Optimized**: Extensive support for Bluetooth keyboards and mice/trackballs.

## Keyboard & Mouse Shortcuts

### Buffer Management
- `Alt + 1` to `Alt + 8` OR `F1` to `F8`: Switch to the corresponding buffer instantly.
- `Alt + B`: Open the **Buffer Selection Menu** overlay (shows filenames if saved).
- `Alt + T`: Open the **Theme Selection Menu** overlay.
- `Alt + M`: Open the **Margin Selection Menu** overlay (Side and Top/Bottom).
- `Alt + F`: Open the **Font Selection Menu** overlay.
- `Alt + H`: Toggle the **Status Bar** visibility (Show/Hide).
- `F9`: Open **Scratchpad** buffer (with char limit).
- `Ctrl + F9`: Flush Scratchpad to log file and clear.
- `Alt + F9`: Flush Scratchpad without saving.
- `Ctrl + Alt + F9`: Open **Scratchpad Settings**.
- `Ctrl + N`: Clear the current buffer (Start over - prompts for confirmation).

### Buffer Selection
When the **Buffer Selection Menu** (`Alt + B`) is open:
- Use **Up/Down Arrows** to navigate.
- Press a number **1-8** to jump instantly to that buffer and close the menu.
- Initial selection will always be your **Current Buffer**.
- `Ctrl + S`: Save current buffer to a named `.txt` file (prompts for name if new).
- `Ctrl + O`: Open an existing `.txt` file into the current buffer.
- `Ctrl + W`: Close the current buffer (clears it and prompts to save if modified).
- `Ctrl + Shift + S`: Save current buffer as a new file (always prompts for name).
- `Ctrl + P`: Export selected buffers to a single **PDF** file.

### Navigation & Editing
- `Arrow Keys`: Move the cursor. (In menus: Move selection).
- `Mouse Click`: Move cursor to clicked position.
- `Mouse Right Click`: Open context menu (Copy/Cut/Paste).
- `Mouse Click + Drag`: Highlight (select) text.
- `Mouse Wheel`: Scroll through text.
- `Shift + Arrow Keys`: Select (Highlight) text.
- `Ctrl + Left/Right`: Jump to previous/next word.
- `Alt + Left/Right`: Jump to beginning/end of line.
- `Alt + Up/Down`: Jump to beginning/end of buffer.
- `Alt + C`: Jump to center of viewport.
- `Alt + V + Left/Right`: Adjust vertical viewport offset (5px steps).
- `F12`: Find cursor (Hold to blink cursor location).
- `Ctrl + Up/Down`: Jump to start of previous/next paragraph.
- `Ctrl + C`: Copy selected text.
- `Ctrl + X`: Cut (Copy and delete) selected text.
- `Ctrl + V`: Paste text from clipboard.
- `Ctrl + Z`: Undo last action.
- `Ctrl + Alt + Z`: Redo last undone action.
- `Ctrl + F`: Open **Find** overlay.
- `Ctrl + R`: Open **Replace** overlay.
- `Ctrl + K`: Bookmark current line.
- `Ctrl + Alt + K`: Open **Bookmark Menu**.
- `Ctrl + Shift + K`: Jump to last bookmark and delete it.
- `Ctrl + Q`: Collapse selected text.
- `Ctrl + Alt + Q`: Open **Collapse Menu** to expand hidden text.

### Find & Replace
When the **Find** or **Replace** overlay is open:
- `Type`: Enter search/replacement text.
- `Tab`: Switch between Find and Replace fields (in Replace mode).
- `Alt + S`: Toggle search scope between **Current Buffer** and **All Buffers**.
- `Enter`: Find next occurrence / Replace current and find next.
- `Ctrl + Enter`: Find previous occurrence (Backward).
- `Up/Down Arrows`: Cycle through search history.
- `Esc`: Close the overlay.
- `Enter`: New line. (In menus: Confirm selection / Find Next).
- `Esc`: Close any open overlay menu.
- `Ctrl + A`: Select all text in current buffer.
- `Backspace`: Delete character before cursor.
- `Delete`: Delete character after cursor.
- `Shift + Delete`: Delete current word.
- `Ctrl + Shift + Delete`: Delete entire line.
- `Enter`: New line.
- `Tab`: Insert 4 spaces.

### View Options
- `Ctrl + =` (or `Ctrl + +`): Increase font size.
- `Ctrl + -`: Decrease font size.
- `Ctrl + T`: Cycle forward through color themes.
- `Ctrl + Alt + T`: Cycle backward through color themes.

## Available Color Themes

You can select these themes via `Alt + T` or cycle through them using `Ctrl + T`.

### Standard Themes
- **Classic**: White text on black background.
- **Retro Terminal**: Green text on black background.
- **High Contrast**: Black text on white background.

### Console & Terminal Themes
- **Wheat**: Dark slate text on cream background.
- **Amber Console**: Amber text on black background.
- **Yellow Moon**: Bright yellow text on deep black background.
- **Wyse Terminal Green**: Classic Wyse green on black.
- **Wyse Terminal Amber**: Classic Wyse amber on black.
- **VS Code Dark**: Light gray text on dark charcoal background.

### E-Ink & Paper Themes
- **Soft Paper Gray**: Dark charcoal text on clean light gray.
- **Cool Light Gray**: Slightly blue-tinted light gray for a modern look.
- **Mid Gray**: Balanced gray for low-glare night writing.
- **Warm Wheat Paper**: Comforting sepia-toned background.
- **Muted Olive Paper**: Subtle green-beige for reduced eye strain.
- **Green-Tinted E-Ink**: Classic digital e-reader appearance.
- **Cool White**: Crisp, bright white with a touch of blue.
- **Soft Blue Paper**: Calm, readable blue-gray.
- **Pale Ice Blue**: Very light blue background with high contrast text.

### Miscellaneous
- **1950s CRT**: Dark gray text on faded paper background.
- **Retro Gray**: Beige text on neutral gray background.
- **Gray 1 & 2**: Various grayscale levels for low strain.
- **Army**: Black text on olive-drab background.

## Available Fonts

You can select these fonts via `Alt + F`.

### Monospaced Fonts
- **Monospace**: Standard system monospaced font.
- **Courier New**: Classic typewriter style.
- **Consolas**: Modern coding font.
- **Lucida Console**: Clean, readable monospace.
- **Roboto Mono**: Google's modern monospaced font.

### Serif Fonts
- **Serif**: Standard system serif font.
- **Times New Roman**: Classic formal serif.
- **Georgia**: Highly readable web serif.

### Sans-Serif Fonts
- **Sans-serif**: Standard system sans-serif font.
- **Arial**: Clean, modern sans-serif.
- **Helvetica**: Classic neutral sans-serif.
- **Verdana**: Designed for screen readability.
- **Trebuchet**: Stylish, modern sans-serif.
- **Noto Sans**: High-quality multilingual sans-serif.

## Daytime & Nighttime Themes
The editor can automatically switch themes based on the time of day.
- Access **Theme Settings** via `Alt + T`.
- Configure individual **Day** and **Night** themes for each buffer.
- Set **Day Start** and **Night Start** times (half-hour increments).
- Choose **Auto** mode to switch based on system clock, or force **Always Day** / **Always Night**.

## Global Settings
- Within the **Margin Selection Menu** (`Alt + M`), you can select **Global Apply Settings**.
- This will copy the current buffer's Theme (Day & Night), Font (Type & Size), and Margin settings to **all 8 buffers** simultaneously.

## Exiting Focus Mode (Immersive Mode)

The app runs in "Focus Mode," which hides the Android status bar and navigation bar to prevent distractions.

To reveal the system bars (to exit the app, check notifications, or use the back button):
1. **Swipe down from the top** of the screen to show the status bar.
2. **Swipe up from the bottom** (or in from the side, depending on your device settings) to show the navigation bar.
3. The bars will automatically hide again after a few seconds of inactivity.

## Tips for Best Experience
- Use a monospaced font-friendly layout (the app defaults to this for clean alignment).
- Connect a Bluetooth keyboard before launching the app for the most seamless "typewriter" feel.
- **Vietnamese Support**: To type in Vietnamese, select the "Tiáº¿ng Viá»‡t" layout in your **Android System Settings > Languages & Input > Physical Keyboard**.
- The status line at the bottom right shows your current Filename, Word Position, and Total Word Count.
