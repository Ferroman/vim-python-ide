Tring to create complete Vim/gVim-based Python IDE.

Done:

* Code Highlight
* Project folder navigation by NERDTree.
* Fast comment/uncomment of code using NERDCommenter plugin (with a little fix).
* Source encodings change.
* On-fly highlighting differences with the repository (svn, cvs, hg, git, Perforce / p4) - svndiff
* Highlight all occurrences of the variable/function/word under cursor
* On-fly code checking by Pylint with errors/warnings highlighting (experimental) and code rate.
* ropevim integration (tested features):
  * Added shortcut hint into menu items (New!)
  * Refactoring:
    * Rename
    * Extract method/local variable
    * Previewing refactoring
    * Undo/redo refactoring
  * Code-assists (added support for Django Managers)
    * Code-completion (Tab key)
    * Goto definition
    * Show pydoc
    * Organize imports (remove unused and duplicate imports and sort them)
* Vim session managment plugin (New!) by sessions
* Json file type support (New!)

In progress: * Project support * Code navigation * Easy external script executing * django support * UnitTest support and code coverage * Debug * Keyboard shortcuts hint

Requirements: * vim/gvim compiled with python support * Terminus font * pylint (pip install pylint) * ropevim (pip install ropevim) * desert256 color scheme (can be changed in .vimrc)
