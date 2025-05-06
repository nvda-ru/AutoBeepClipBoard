# AutoBeepClipboard (Clipboard with Automatic Sound Notification)

The AutoBeepClipBoard add-on simply emits a short sound when any new text or file is automatically placed into the clipboard.
Whenever selected text or a file is copied to the clipboard using the usual mouse actions, the copy command Control+C (or pressing Control+Insert twice), the cut command Control+X,
or — for text only — by clicking a copy button on a website or in an application, you will hear a short sound indicating that the newly copied text has indeed been placed into the clipboard.
If such text or file is already in the clipboard, you will not hear the short sound.

### Keyboard Shortcut:

* NVDA+Control+Shift+A: Toggles the sound notification for clipboard changes on or off.

The keyboard shortcut can be changed in the Input Gestures dialog under the "Clipboard with Automatic Sound Notification" category.

In the settings, there is a checkbox labeled "Enable sound notification for clipboard changes," which controls whether the add-on's functionality is enabled when NVDA starts.

Please note that this add-on does not replace add-ons that announce all pressed commands, such as Copy, Cut, Paste, Undo, or Select All.
It only checks whether something new has been placed into the clipboard, whether it was copied or cut, and emits a short sound if there is something new.

### Note:

The AutoBeepClipboard add-on is a modification of the AutoBeepTextClipboard add-on.
The latter emits a sound only when new text is placed into the clipboard, while the former emits the same short sound when any new file is placed into the clipboard.
If no sound is heard, it means the clipboard already contains the same text or the same file.

### Changelog

#### 2025.05.02

* Added a keyboard shortcut and a category in Input Gestures.
* Added a checkbox in settings to enable or disable the add-on's functionality when NVDA starts.
* Settings are preserved across NVDA sessions.
* Added localization.
* Updated the help guide.

#### 2025.01.20

* Initial release.
* The add-on had no settings or keyboard shortcuts at this stage.
