# TabAttack

Save browser memory by exporting your tabs as Markdown. The extension allows you to edit the document in a text editor as you wish before you save it.

Later, you can import these Markdown documents and restore all windows exactly like they were before.

## Installation

Get the extension from the [Chrome Web Store](https://chrome.google.com/webstore/detail/tabattack/ginflokhdahakklidfjlogllkkhokidj).

## Features

The extension adds a tab counter to the toolbar:

![Tab counter](https://cloud.githubusercontent.com/assets/704336/6197251/9ea23dbe-b3e2-11e4-9e96-92f5f2783b85.png)

When you click it, you will see an overview of all tabs (organized by window) that you have open:

![Exported tabs](https://cloud.githubusercontent.com/assets/704336/6196991/056f4392-b3df-11e4-871e-33ed649db893.png)

You can now edit the document as you wish. After that you can:

- Download the current state of the editor as a *.md file

- Close all tabs (except the current one)

- Open a file that you saved earlier (drag and drop on top of the editor also works)

- Re-open all links as individial tabs that are currently in the editor. This will restore each unordered list in its own window. This whole acion only works if all links are inside of an unordered list, though.

There are keyboard shortcuts for these actions:

Action | OS X | Windows
-------|------|--------
Download | ⌘S | Ctrl+S
Close all tabs | ⌘Q | Ctrl+Q
Open a file | ⌘O | Ctrl+O
Open all links | ⇧⌘O | Ctrl+Shift+O

Furthermore, there are [many keyboard shortcuts for using the Ace editor](https://github.com/ajaxorg/ace/wiki/Default-Keyboard-Shortcuts).

## Browser keyboard shortcuts

This extension also adds a few useful, general tab management keyboard shortcuts. Most of them have to be set manually by going to “Keyboard shortcuts” at the bottom of [chrome://extensions/](chrome://extensions/).

![Keyboard shortcut overview](https://cloud.githubusercontent.com/assets/704336/6196998/16341fe0-b3df-11e4-8dcb-a58665ffd354.png)

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)