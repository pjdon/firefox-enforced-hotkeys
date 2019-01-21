# Firefox Enforced Hotkeys

Firefox provides a [list of keyboard shortcuts/hotkeys](https://support.mozilla.org/en-US/kb/keyboard-shortcuts-perform-firefox-tasks-quickly). Most of these can be captured using an [`addEventListener`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener) and have their default action (e.g. reload the tab) prevented using [`preventDefault`](https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault).

Below is a list of hotkeys that when entered in the web page, either can't be captured with JavaScript and/or will always perform their default action. This means the particular hotkey can't be used for actions inside the web page or rebound by extensions such as [SakaKey](https://addons.mozilla.org/en-GB/firefox/addon/saka-key/?src=search) and [Shortkeys](https://addons.mozilla.org/en-GB/firefox/addon/shortkeys/).

### Notes:
Currently this list only contains results for Windows 10 and Firefox 64

## Key press can be captured, but default action still occurs.
Default Action | Shortcut
--- | ---
Toggle Menu Bar | `Alt`

## Key press cannot be captured nor default action action prevented
Default Action | Shortcut
--- | ---
Close Tab (except pinned) | `Ctrl` + `W`<br> `Ctrl` + `F4`
Close Window |  `Ctrl` + `Shift` + `W`<br>`Alt` + `F4`
Exit | `Ctrl` + `Shift` + `Q`
Cycle Tabs | `Ctrl` + `Tab`<br>`Ctrl` + `Shift` + `Tab`<br>`Ctrl` + `Page Up`<br>`Ctrl` + `Page Down`
Move Tab | `Ctrl` + `Shift` + `Page Up`<br>	`Ctrl` + `Shift` + `Page Down`
New Tab | `Ctrl` + `T`
New Window | `Ctrl` + `N`
