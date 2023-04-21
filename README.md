# AppleScript App Template for Xcode (AppleScriptObjC)

Unfortunately Apple seams to push developers to drop writing AppleScript apps (AppleScriptObjC) by dropping the corresponding project template from latest Xcode releases (14.3+). 

For anyone that is missing an older Xcode installation to pull the AppleScript App template from, I published it here.

## Installation instructions

1. Right-click the Xcode app in Finder.
2. Choose "Show package content" from the context menu.
3. Navigate to `Applications` > `Xcode.app` > `Contents` > `Developer` > `Library` > `Xcode` > `Templates` > `Project\ Templates` > `macOS` > `Other`.
	- If one of the folders is missing, create it.
4. Copy or move the template to this folder.
5. Restart Xcode.
6. To validate the installation proceed as follows in Xcode:
	1. Choose `File` > `New` > `New project...`.
	2. Check if `Apple Script App` is available in the `Other` section under the `macOS` tab.

Have fun.