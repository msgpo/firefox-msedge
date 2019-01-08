Make Firefox look like Edge
===========================

Like the clean, integrated look of MS Edge, but prefer everything else about Firefox?
Good news, it only takes a few steps to customize the look of Firefox.

1. Open firefox, go to Customize, and change the theme to "Light".

2. In firefox, enter the URL [about:support](about:support). Scroll down to "Profile Folder" and click "open folder".

3. In that folder, create a new folder called "chrome". Then copy the userChrome.css from this repo into that folder.
If you already have a userChrome.css file, you might want to copy it or back it up before replacing it.

4. Close and re-open Firefox.

Todo
----
* Optimize userChrome.css rules to only apply when light theme is selected.
* Add support for dak theme.
