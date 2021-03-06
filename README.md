# Functionality

Mark lines in the editor and easily jump to them.

# Usage

### Availble commands

* **Bookmarks: Toggle** Mark/unmark lines with bookmarks
* **Bookmarks: Jump to Next** Move the cursor forward, to the bookmark below
* **Bookmarks: Jump to Previous** Move the cursor backward, to the bookmark above
* **Bookmarks: Clear** remove all bookmarks from the current file

![Commands](images/bookmarks-commands.png)

### Toggle Bookmark

You can easily Mark/Unmark bookmarks on any line. Works even for wrapped lines.

![Toggle](images/bookmarks-toggle.png)

### Project and Session Based

The bookmarks are saved _per session_ for the project that you are using. You don�t have to worry about closing files in _Working Files_. When you reopen the file, the bookmaks are restored.

It also works even if you only _preview_ a file (simple click in TreeView). You can put bookmarks in any file and when you preview it again, the bookmarks will be there.

## TODO List

Here are some ideas that will be added soon:

* **Save bookmarks between sessions:** Allow the bookmarks to be saved and restored, even if you close **Code** or change the active Project/Folder.
* **Preview bookmarked lines:** Create a new command (**Bookmarks: List**) that will show all bookmarked lines, with its content, so you easily identify which bookmark you would want to go.
* **Change the bookmark icon:** Allow you to define which icon do you want to use as bookmark

## Known Issues

- Hiting `Enter` in lines with bookmarks, temporarily also moves the bookmarks, but when you stop typing, the bookmark is correctly presented on the original line.

## Participate

If you have any idea, feel free to create issues and pull requests