Become a VSCode Power User

VSCode
Settings
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
"editor.formatOnSave": true,
// Enable per-language
"[javascript]": {
"editor.formatOnSave": true
},
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
"terminal.integrated.fontSize": 24,
"terminal.integrated.lineHeight": 1,
"terminal.integrated.fontFamily": "Ubuntu mono",
"window.zoomLevel": 2,
"todohighlight.isEnable": true,
"todohighlight.keywords": [
"TBD",
"TODO"
],
"workbench.startupEditor": "newUntitledFile",
"explorer.confirmDragAndDrop": false,
"explorer.confirmDelete": false,
"cSpell.userWords": [
"airfec",
]
}

    Keybindings
        Bubbling line
        Duplicate line
            iOS
            `[
                {
                    "key": "cmd+shift+up",
                    "command": "editor.action.moveLinesUpAction",
                    "when": "editorTextFocus"
                },
                {
                    "key": "cmd+shift+down",
                    "command": "editor.action.moveLinesDownAction",
                    "when": "editorTextFocus"
                },
                {
                    //duplicate
                    "key": "cmd+shift+d",
                    "command": "editor.action.copyLinesDownAction",
                    "when": "editorTextFocus && !editorReadonly"
                }
                ]`
            Linux
                [
                    {
                        "key": "ctrl+shift+up",
                        "command": "editor.action.moveLinesUpAction",
                        "when": "editorTextFocus"
                    },
                    {
                        "key": "ctrl+shift+down",
                        "command": "editor.action.moveLinesDownAction",
                        "when": "editorTextFocus"
                    },
                    {
                        "key": "ctrl+shift+alt+d",
                        "command": "workbench.view.debug"
                    },
                    {
                        "key": "ctrl+shift+d",
                        "command": "-workbench.view.debug"
                    },
                    {
                        "key": "ctrl+shift+d",
                        "command": "editor.action.copyLinesDownAction",
                        "when": "editorTextFocus && !editorReadonly"
                    },
                    {
                        "key": "ctrl+shift+alt+down",
                        "command": "-editor.action.copyLinesDownAction",
                        "when": "editorTextFocus && !editorReadonly"
                    }
                ]
        Cut line
            ctrl/cmd x
        Select multiple items
            ctrl/cmd d
    Debugger
        https://code.visualstudio.com/docs/editor/debugging
    Git Tracker
        https://code.visualstudio.com/docs/editor/versioncontrol
    Terminal
        // USE IT
        // STYLE IT
    Extensions
        AutoClose Tag
            `code --install-extension formulahendry.auto-close-tag`
        AutoImport
            `code --install-extension steoates.autoimport`
        AutoRename Tag
            `code --install-extension formulahendry.auto-rename-tag`
        Cobalt2
            `code --install-extension wesbos.theme-cobalt2`
        Code Spell Checker
            `code --install-extension streetsidesoftware.code-spell-checker`
        Color Highlight - css
            `code --install-extension naumovs.color-highlight`
        Docker
            `code --install-extension peterjausovec.vscode-docker`
        ESLint
            `code --install-extension dbaeumer.vscode-eslint`
        Git History
            `code --install-extension donjayamanne.githistory`
        CSS ClassNames
            `code --install-extension zignd.html-css-class-completion`
        NodeJS Modules
            `code --install-extension leizongmin.node-module-intellisense`
        ***Prettier***
            `code --install-extension esbenp.prettier-vscode`
        TODO Highlight
            `code --install-extension wayou.vscode-todo-highlight`
        Trailing Spaces
            `code --install-extension shardulm94.trailing-spaces`
        VSCode Icons
            `code --install-extension robertohuertasm.vscode-icons`
        VSCode Random
            `code --install-extension jrebocho.vscode-random`

    Emmett
        https://docs.emmet.io/
        https://docs.emmet.io/cheat-sheet/