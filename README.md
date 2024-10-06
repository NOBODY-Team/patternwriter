# [directory](https://nobodyteam.com)

# PatternWriter
Ultraminimalistic open-source writing software.

# Functionality

## Writing

PatternWriter utilizes writing based on richtext markdown, rather than UI input.

> [DISCLAIMER]

> PatternWriter only currently supports one singular font, Courier New, although this will change in the future. Text is bold by default because of this.

### PatternWriter Richtext Writing Reference

| Functionality | Explanation | Example |
| --- | --- | --- |
| `Font Size - <size=[number]>` | The size of the font. Default is 14. | `<size=32>Hello` would output `Hello` with the font size 32. |
| `Text Alignment - <align=[left/center/right]>` | The alignment of the written text. | `<align=center>Hello` would output the text `Hello` aligned to the center of the writing field. |
| `Font Color - <color=[color]>` | The color of the font. Default is black. | `<color=cyan>Hello` would output the text `Hello` as blue.  |
| `Italics - <i>[text]</i>` | Italic text. | `<i>Hello</i>` would output `Hello` as italic. |

## Text Editing Window

Writing in PatternWriter works in either the base writing window, or the Text Element window, which can be accessed with the keyboard input `ctrl + tab`.

In the Text Element window, you are capable of seeing richtext instead of having it be automatically converted to markdown, and capable of using keycodes for quick richtext.

*Richtext works in the main window, but it will automatically be converted to markdown

![pwtextelementexample1](https://github.com/user-attachments/assets/479bb546-4bc0-4587-a8e2-98086452a8a0) ![pwtextelementexample2](https://github.com/user-attachments/assets/d17796e7-6b3d-4a2e-9019-d659dd82657a)

Pressing `Submit` will output the written text to the main window.

![pwtextelementexample3](https://github.com/user-attachments/assets/4d89cea6-f7c8-4d2a-b415-5c6a487c0d55)

### PatternWriter Text Element Window Keycode Reference

| Keycode | Output |
| `<` | `<>` |
| `ctrl + s` | `<size=>` |
| `ctrl + d` | `<align=>` |
| `ctrl + i` | `<i></i>` |
| `ctrl + b` | `<b></b>` |
