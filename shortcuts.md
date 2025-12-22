# Shortucts

`Ctrl + K Ctrl + S` — Open the keyboard shortcuts config

or

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf


## Editing

Keyboard shortcut      | Action
-----------------------|--------------------------------------------------
`Alt + ↑/↓`            | Move a line up/down
`Shift + Alt + ↑/↓`    | Copy a line up/down
`Ctrl + é`             | Toggle line comment
`Ctrl + Enter`         | Add newline below
`Shift + Ctrl + Enter` | Add newline above
`Ctrl + ¸`             | Indent line
`Ctrl + ^`             | Outdent line


## Navigation

Keyboard shortcut      | Action
-----------------------|--------------------------------------------------
`Ctrl + P`             | Go to file (quick open)
`Ctrl + G`             | Go to line
`Ctrl + T`             | Go to symbol across all file
`Ctrl + Shift + O`     | Go to symbol in the current file
`Alt + ←/→`            | Go back/foward (history of commands)
`Ctrl + Shift + <`     | Go to the matching bracket
`F12`                  | Go to definition of this symbol
`Ctrl + F12`           | Go to implementations of this interface
`Shift + F12`          | Go to references (where that symbol is used)


## Cursors and selection

Keyboard shortcut      | Action
-----------------------|--------------------------------------------------
`Alt + Click`          | Insert cursor
`Shift + Alt + i`      | Add cursors to line end
`Ctrl + Alt + ↑/↓`     | Add cursor above/below
`Ctrl + U`             | Undo last cursor operation
`Ctrl + D`             | Select next occurrence of word
`Ctrl + Shift + L`     | Select all occurrences of selected text
`Shift + Alt + ←/→`    | Shrink/expand selection (code block)
`Ctrl + L`             | Select current line


## UI

Keyboard shortcut      | Action
-----------------------|--------------------------------------------------
`Ctrl + B`             | Toggle sidebar
`Ctrl + 0`             | Go to sidebar
`Ctrl + 1`             | Go to main editor
`Ctrl + Shift + E`     | File explorer (sidebar)
`Ctrl + Shift + F`     | Search (sidebar)
`Ctrl + Shift + G`     | Git (sidebar)
`Ctrl + Shift + D`     | Debug (sidebar)
`Ctrl + Shift + M`     | Problems (bottom bar)
`Ctrl + Shift + U`     | Output (bottom bar)
`Ctrl + è`             | Terminal (bottom bar)
`Ctrl + J`             | Toggle bottom panel


## AI

Keyboard shortcut      | Action
-----------------------|--------------------------------------------------
`Ctrl + i`             | Inline chat
`Ctrl + Shift + i`     | Sidebar chat


# Rich languages editing

Keyboard shortcut      | Action
-----------------------|--------------------------------------------------
`Ctrl + .`             | Quick fix
`Ctrl + K, Ctrl + X`   | Trim trailling white space


## Others

Keyboard shortcut      | Action
-----------------------|--------------------------------------------------
`Ctrl + <`             | Split editor
`Ctrl + Shift + P`     | Command palette
`F1`                   | Command palette
`Alt + PgUp/PgDn`      | Scroll page up/down (without moving the cursor)


# Advanced features explanation

## Quick open `CTRL + P`

Search for file by file name. It support fuzzy search and PascalCase search using only the upper cased letter.

By default it show you recently opened files including opened tab.

- `Enter`        — Open the file and close **Quick open**
- `Ctrl + Enter` — Open the file to the side and close **Quick open**
- `→`            — Open the file and keep **Quick open** open


## Go to Line `CTRL + G`

- Format `:rownum:colnum`
- You can use nagative indexing to go to line at the end (-1 is the last line)
- You can add those code at the end of a file with **Quick open**
- If you don't press `Enter` it only preview the location


## Go to symbol in the current file `CTRL + Shift + O`

- Format `@symbol`
- Everything that has meaning in a programming language is a symbol (class, variable, object, ...)
- Using ↑/↓ allow you to preview your symbol in the current file
- All symbols show up ordered by their position in the file but if you add `:` they are ordered by type
- You can use thise symbol with **Quick open**


# Converting keyboard shortcut from en_US to fr_CA

en_US | fr_CA
------|------
\     | <
/     | é
^     | [
¸     | ]