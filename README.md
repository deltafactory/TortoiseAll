TortoiseAll
=============
TortoiseAll is just Git and Hg extensions of the ideas seen in brilliant [TortoiseSVN](https://sublime.wbond.net/packages/TortoiseSVN).

TortoiseSVN is a tiny and simple plugin for [Sublime Text](http://www.sublimetext.com) .
It's behavior is similar to [subclipse](http://subclipse.tigris.org/) in [Eclipse](http://www.eclipse.org/).
**It runs only on Windows and needs the TortoiseSVN command line tools (TortoiseProc.exe), TortoiseGit command line tools (TortoiseGitProc.exe), TortoiseHg command line tools (thg.exe),.**

Usage
============
Install it using [Sublime Package Control](http://wbond.net/sublime_packages/package_control).

You can call TortoiseAll commands through Command Palette or folders context menu in the sidebar.

If TortoiseSVN is not installed at `C:\\Program Files\\TortoiseSVN\\bin\\TortoiseProc.exe`, specify the correct path
by setting property "tortoiseproc_path" in your TortoiseAll.sublime-settings file.  
If TortoiseGit is not installed at `C:\\Program Files\\TortoiseGit\\bin\\TortoiseGitProc.exe`, specify the correct path
by setting property "tortoisegitproc_path" in your TortoiseAll.sublime-settings file.  
If TortoiseHG is not installed at `C:\\Program Files\\TortoiseHg\\thg.exe`, specify the correct path
by setting property "tortoisehgproc_path" in your TortoiseAll.sublime-settings file.


IMPORTANT
==============

Do NOT edit the default TortoiseAll settings. Your changes will be lost
when TortoiseAll is updated. ALWAYS edit the user TortoiseAll settings
by selecting "Preferences->Package Settings->TortoiseAll->Settings - User".
Note that individual settings you include in your user settings will **completely**
replace the corresponding default setting, so you must provide that setting in its entirety.

Settings
==============

If your TortoiseProc.exe path is not the default, please modify the path by selecting 
"Preferences->Package Settings->TortoiseAll->Settings - User" in the menu.

The default setting is:

    {
        // Auto close update/pull dialog when no errors, conflicts and merges
        "autoCloseUpdatePullDialog": true,
        // Auto close commit/push dialog when no errors, conflicts and merges
        "autoCloseCommitPushDialog": true,
        // Always open HgWorkbench in new window
        "newHgWorkbench": true,
        "tortoiseproc_path": "C:\\Program Files\\TortoiseSVN\\bin\\TortoiseProc.exe",
        "tortoisegitproc_path": "C:\\Program Files\\TortoiseGit\\bin\\TortoiseGitProc.exe",
        "tortoisehg_path": "C:\\Program Files\\TortoiseHg\\thg.exe",
    }
