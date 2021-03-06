# Part 2 - Become a VSCode Power User

## Table of Contents

1.  [Introduction](#why-are-you-reading-this)
2.  [Part 2](#why-are-you-reading-this)
3.  [Part 3](#why-are-you-reading-this)
4.  [Part 4](#why-are-you-reading-this)

---

> _Weeks of coding can save you hours of planning. - Unknown_

---

## VSCode Command Palette

https://code.visualstudio.com/docs/getstarted/userinterface

## VSCode Settings

To open settings with the command line

```javascript
    {
    // An array of languages where Emmet abbreviations should not be expanded.
    "emmet.excludeLanguages": [
    "markdown"
    ],
    // Path to a folder containing Emmet profiles and snippets.'
    // Enable Emmet abbreviations in languages that are not supported by default. Add a mapping here between the language and emmet supported language.
    // E.g.: {"vue-html": "html", "javascript": "javascriptreact"}
    "emmet.includeLanguages": {},
    // When set to false, the whole file is parsed to determine if current position is valid for expanding Emmet abbreviations. When set to true, only the content around the current position in css/scss/less files is parsed.
    "emmet.optimizeStylesheetParsing": true,
    // Preferences used to modify behavior of some actions and resolvers of Emmet.
    "emmet.preferences": {},
    // Shows possible Emmet abbreviations as suggestions. Not applicable in stylesheets or when emmet.showExpandedAbbreviation is set to "never".
    "emmet.showAbbreviationSuggestions": true,
    // Shows expanded Emmet abbreviations as suggestions.
    // The option "inMarkupAndStylesheetFilesOnly" applies to html, haml, jade, slim, xml, xsl, css, scss, sass, less and stylus.
    // The option "always" applies to all parts of the file regardless of markup/css.
    "emmet.showExpandedAbbreviation": "always",
    // If true, then Emmet suggestions will show up as snippets allowing you to order them as per editor.snippetSuggestions setting.
    "emmet.showSuggestionsAsSnippets": false,
    // Define profile for specified syntax or use your own profile with specific rules.
    "emmet.syntaxProfiles": {},
    // When enabled, Emmet abbreviations are expanded when pressing TAB.
    "emmet.triggerExpansionOnTab": false,
    // Variables to be used in Emmet snippets
    "emmet.variables": {},
    //Prettier settings
    // Set the default
    }
```

```javascript
    {
    "editor.formatOnSave": true,
    // Enable per-language
    "[javascript]": {
    "editor.formatOnSave": true
    }
```

```javascript
    {
    //Theme settings
    "workbench.colorTheme": "Cobalt2",
    "editor.fontFamily": "Inconsolata, Operator Mono, Menlo, Monaco, 'Courier New', monospace",
    "editor.fontSize": 20,
    "editor.lineHeight": 25,
    "editor.letterSpacing": 0.5,
    "files.trimTrailingWhitespace": true,
    "editor.fontWeight": "400",
    "prettier.eslintIntegration": true,
    "editor.cursorStyle": "line",
    "editor.cursorWidth": 5,
    "editor.cursorBlinking": "solid",
    "editor.wordWrap": "on",
    "editor.renderWhitespace": "all",
    "window.zoomLevel": 2,
    "workbench.startupEditor": "newUntitledFile",
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
}
```

```javascript
{
    "terminal.integrated.fontSize": 24,
    "terminal.integrated.lineHeight": 1,
    "terminal.integrated.fontFamily": "Ubuntu mono"
}
```

### TODO Highlighter Specific Settings

```javascript
{
    "todohighlight.isEnable": true,
    "todohighlight.keywords": [
      "TBD",
      "TODO"
    ]
}
```

### cSpell Checker Specific Settings

```javascript
{
    "cSpell.userWords": [
      "exampleWordToAddToGlobalDictionary",
    ]
}
```

## VSCode Keybindings

### iOS Keybindings

```javascript
[
  {
    // bubble move a line up
    key: "cmd+shift+up",
    command: "editor.action.moveLinesUpAction",
    when: "editorTextFocus"
  },
  {
    // bubble move a line down
    key: "cmd+shift+down",
    command: "editor.action.moveLinesDownAction",
    when: "editorTextFocus"
  },
  {
    // duplicate a line
    key: "cmd+shift+d",
    command: "editor.action.copyLinesDownAction",
    when: "editorTextFocus && !editorReadonly"
  }
];
```

### Linux Keybindings

```javascript
[
  {
    key: "ctrl+shift+up",
    command: "editor.action.moveLinesUpAction",
    when: "editorTextFocus"
  },
  {
    key: "ctrl+shift+down",
    command: "editor.action.moveLinesDownAction",
    when: "editorTextFocus"
  },
  {
    key: "ctrl+shift+alt+d",
    command: "workbench.view.debug"
  },
  {
    key: "ctrl+shift+d",
    command: "-workbench.view.debug"
  },
  {
    key: "ctrl+shift+d",
    command: "editor.action.copyLinesDownAction",
    when: "editorTextFocus && !editorReadonly"
  },
  {
    key: "ctrl+shift+alt+down",
    command: "-editor.action.copyLinesDownAction",
    when: "editorTextFocus && !editorReadonly"
  }
];
```

---

> _Linux is only free if your time has no value. - Jamie Zawinski_

---

## VSCode Shortcuts to memorize

### Cut line

`ctrl/cmd x`

### Select multiple items

`ctrl/cmd d`

## VSCode Debugger

https://code.visualstudio.com/docs/editor/debugging

## VSCode Source Control

https://code.visualstudio.com/docs/editor/versioncontrol

## VSCode Terminal

// USE IT
// STYLE IT

## VSCode Extensions

### AutoClose Tag

```sh
code --install-extension formulahendry.auto-close-tag
```

### AutoImport

```sh
code --install-extension steoates.autoimport
```

### AutoRename Tag

```sh
code --install-extension formulahendry.auto-rename-tag
```

### Cobalt2

```sh
code --install-extension wesbos.theme-cobalt2
```

### Code Spell Checker

```sh
code --install-extension streetsidesoftware.code-spell-checker
```

### Color Highlight - css

```sh
code --install-extension naumovs.color-highlight
```

### Docker

```sh
code --install-extension peterjausovec.vscode-docker
```

### ESLint

```sh
code --install-extension dbaeumer.vscode-eslint
```

### Git History

```sh
code --install-extension donjayamanne.githistory
```

### CSS ClassNames

```sh
code --install-extension zignd.html-css-class-completion
```

### NodeJS Modules

```sh
code --install-extension leizongmin.node-module-intellisense
```

### Prettier - Possible the best extension ever made

```sh
code --install-extension esbenp.prettier-vscode
```

### TODO Highlight

```sh
code --install-extension wayou.vscode-todo-highlight
```

### Trailing Spaces

```sh
code --install-extension shardulm94.trailing-spaces
```

### VSCode Icons

```sh
code --install-extension robertohuertasm.vscode-icons
```

### VSCode Random

```sh
code --install-extension jrebocho.vscode-random
```

## Emmet - Built into VSCode

https://docs.emmet.io/
https://docs.emmet.io/cheat-sheet/

#### What we learned

- Make good commit messages
- Write code that future you will enjoy reading
- Make good commit messages

[Go to Part 3 - Code Faster/Better/Stronger at Hack Reactor](https://github.com/nvincenthill/streamlineyourworkflow/tree/master/Part%203/PART3.md)
