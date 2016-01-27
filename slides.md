title: One month with VS Code
author:
  name: Daniel Paz-Soldan
  twitter: danpazsoldan
output: index.html
controls: true

--

# One month with VS Code
## January 27, 2016

--

### Why VS Code?

https://code.visualstudio.com/docs/editor/whyvscode

- "Code is more than just text"
- Understands your code
- Debugging!
- Works out of the box (mostly)

--

### Awesome features

- Node is a first class citizen (also C# and TypeScript)
- Intellisense
- In-editor debugging
- [Lint/validation errors and warnings with eslint plugin](https://code.visualstudio.com/Docs/languages/javascript#_javascript-linters-eslint-jshint)
- Git (branch, checkout, push, pull, diff, gutter indicators)
- Command palette

--

### Not so awesome features

- Limited git support (stash, rebase, checkout remotes)
- Goto, especially in deeply nested directory trees
- [Intellisense without TypeScript](https://code.visualstudio.com/docs/languages/javascript)
- Lack of remote debugging e.g. for Docker (on roadmap)
- Electron Shell

--

### Nits

- [Missing end_of_file_newline_on_save](https://visualstudio.uservoice.com/forums/293070-visual-studio-code/suggestions/8298222-add-new-line-at-the-end-file-on-save)
- [Column indicator at col 80](https://visualstudio.uservoice.com/forums/293070-visual-studio-code/suggestions/7756947-column-indicator-at-80-columns)
- Dealing with node version manager
- Have to add a line to .gitignore
- Warning on global vars e.g. in mocha tests
- Missing a [good auto-jsdocs plugin](https://marketplace.visualstudio.com/items/stevencl.addDocComments)

--

### Live coding

- New feature git workflow
- Debugging

--

### Tips n' Tricks

- Navigate recently opened files (Ctrl + Tab)
- F2 to rename symbol
- Expand and shrink selection
- Goto definition and peek definition
- Diff any two files
- Diff inline / side-by-side views
- [Key shortcuts](https://code.visualstudio.com/docs/customization/keybindings)

--

### What I haven't looked at
- Tasks - grunt tasks automatically recognized
- Typings/TypeScript
- Webstorm, etc.

--

### Conclusion
- Code has a rich dev environment without the weight of a full IDE
- Sublime Text continues to be great for editing text
- Give it a try!
