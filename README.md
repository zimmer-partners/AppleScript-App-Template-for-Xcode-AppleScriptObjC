# AppleScript App Template for Xcode (AppleScriptObjC)

Apple appears to be discouraging developers from writing AppleScript (AppleScriptObjC) apps by removing the corresponding project template from recent Xcode releases (14.3+).

As a result, it may be difficult for developers to access the AppleScript App template, which was available in older versions of Xcode. However, to assist those who are missing this template, I have published it here for download.

## Installation instructions

1. Right-click the Xcode app in Finder.
2. Choose `Show package content` from the context menu.
3. Navigate to `Contents` > `Developer` > `Library` > `Xcode` > `Templates` > `Project\ Templates` > `macOS` > `Other`.
	- If one of the folders is missing, create it.
4. Copy or move the template to this folder.
5. Restart Xcode.
6. To validate the installation proceed as follows in Xcode:
	1. Choose `File` > `New` > `New project...`.
	2. Check if `Apple Script App` is available in the `Other` section under the `macOS` tab.

Have fun.