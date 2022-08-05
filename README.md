# The Speed of Write

**Async talk 2022-08-04 by Jake 'Sid' Smith**

## Introduction

### About me

My name is Jake. I'm currently self employed, but I've been working in the app design/development industry for about 10 years at various agencies.

I come from a design background, but gradually transitioned into a mostly development role.

I'd been teaching myself code for fun in my spare time (or during classes at school when I should have been making powerpoint presentations or whatever) since I was about 14.

I now almost exclusively write TypeScript and work on mainly React and React Native apps, and am currently working full stack on a pair of React and React Native apps with an node backend.

### The talk

This talk is about how to improve how we write code, in terms of quality, consistency, and speed - how we can better utilize our editors and other tools to save us time.

For the first part of the session I will be covering some tools, settings, shortcuts, and editor extensions I use or know of to increase your coding quality/speed. These will mostly center around VSCode, but many will be applicable to other popular editors.

After this initial demo I'll open the floor for others to suggest ways in which we can improve how we code - shortcuts, extensions, other tools, etc, and demo some of the suggestions.

**Note: my shortcuts may vary from yours as I am using Atom keybindings, plus some from Sublime, and a bunch of custom ones, additionally some of the extensions I use may now come with VSCode or other editors out of the box.**

## The command pallette

- Search for commands (CMD + SHIFT + P)
- Search for files (CMD + P)
- Symbol in file (CMD + G)
- Symbol in workspace
- Symbol in editor
- Adjust settings via UI or JSON (CMD + Comma)

## Useful settings

- Trim trailing whitespace
- Trim trailing newlines
- Add final newline
- Auto format on edit, paste, save
- Bracket pair colorization
- Editor label format

You can find these and some more of the settings I use in [here](vscode/settings.json).

## Shortcuts

- Open/close the terminal (CMD + Backtick)
- Multi-cursor (CMD + Click)
- Select multi lines (CMD + SHIFT + Click)
- Select next (CMD + D)
- Skip over words/end of lines (ALT + Arrows/CMD + Arrows, and camel case navigation)
- Move line(s) up/down (ALT + Arrows)
- Cut/paste a line (with a cursor on the line CMD + X and then CMD + v)
- Quickly duplicate a line above/below (ALT + SHIFT + Arrows)
- Add additional cursor above/below (CMD + ALT + Arrows)
- Add cursor at end of lines (CMD + L)
- Rename symbol
- Go to bracket
- Go to definition
- Go to type definition
- Find all references
- Find all implementations
- Quick fix (CMD + Period)

## Extensions

### Code quality/consistency

- [Editorconfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Code spell checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

### Improve speed

- [Auto close tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Change case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)
- [Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)
- [Remove empty lines](https://marketplace.visualstudio.com/items?itemName=usernamehw.remove-empty-lines)
- [File utils (duplicate file)](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)
- [Camel case navigation](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)

### Improve collaboration

- [Git blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Live share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)
- [WSL (run Linux in Windows)](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)

### Visibility

- Markdown preview - now appears to be built in
- [Color highlight - somewhat built in](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
- [TODO highlight - probably built in](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [TODO tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [Word count](https://marketplace.visualstudio.com/items?itemName=rido3.wordcount)
- [File size](https://marketplace.visualstudio.com/items?itemName=zh9528.file-size)
- [Presentation mode - probably built in](https://marketplace.visualstudio.com/items?itemName=jspolancor.presentationmode)
- [Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)

### Refactoring

- [React refactor](https://marketplace.visualstudio.com/items?itemName=iceworks-team.iceworks-refactor)
- [Resharper (.NET - Visual Studio - expensive)](https://www.jetbrains.com/resharper/)

### Mind blowing

- [Quokka.js (run JavaScript in VSCode)](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
- [GitHub copilot (use AI to write your code)](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

## Snippets and custom shortcuts

- Code > Preferences > Configure User Snippets
- Code > Preferences > Keyboard Shortcuts
- Key chords (combine 2 keyboard shortcuts)

You can finds some of the snippets I personally use (some are pretty outdated now) [here](vscode/snippets/).

There's also some examples of the key chords I use in [here](vscode/keybindings.json).

Note: commands beginning with `-` means it is unbinding that shortcut.

## Other tools

- Dot files repo
- [Github Desktop (Git UI)](https://desktop.github.com/)
- [Tower (Git UI)](https://www.git-tower.com/mac)
- [Sourcetree (Git UI)](https://www.sourcetreeapp.com/)
- [Git Kraken (Git UI)](https://www.gitkraken.com/)
- [Gitify (GitHub notifications on your desktop)](https://www.gitify.io/)
- [Better Touch Tool (window snapping, shortcuts, gestures, touch bar customization)](https://folivora.ai/)
