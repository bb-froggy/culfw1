# culfw

The source code is cloned from https://sourceforge.net/projects/culfw/ via [svn2github](https://github.com/svn2github). It is the [culfw firmware](http://culfw.de/culfw.html) for the CUL family of devices.

The culfw Homepage contains version 1.67, but that version misses a few changes made to the SVN repository afterwards. Especially WMBUS Type C.

This GitHub repository contains an action compiling the source code to the hex files you can flash to your CUL. The latest version is available compiled as Release.

If you want to adapt some settings for your CUL, just fork the repository, edit the source files and run the action in your fork to get your own custom hex files.

## License

culfw itself is GPL'ed, so the build files are available under GPL, too.

You can also choose to use the the build files (but not the culfw source code) under the terms of the MIT license, if you want.
