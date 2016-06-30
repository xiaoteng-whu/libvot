## libvot Coding Style

### Contribute to libvot
Thanks for your interests in contributing code to *libvot*! Before send your code, we'd like to bring your attention about the coding style of *libvot*.

There are two important rules to follow:
* When making changes, try to conform with the style and conventions of the surrounding code.

* Strive for clarity, even if it occasionally breaks the guidelines. After all, coding styles are applied to facilitate the development process, rather than against it.

Other guidelines include:
* We largely follow [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html).

* Tab size: 4 spaces, feel free to use tab or spaces, tab is set to 4 spaces.

* All file names are in lowercase letters, with hyphen ('-') to connect words.

* Documentation: use [Doxygen comment style](http://www.stack.nl/~dimitri/doxygen/manual/docblocks.html) to comment your code.

* git usage:
    - each commit message should start with '+' for bringing in new features, '*' for modification of existing code, and '-' for removal of a feature/module.
    - use `git pull --rebase` to synchronize with upstream, because we are aiming for a linear commit history.