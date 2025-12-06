# Shortucts

`CTRL+K CTRL+S` — Open the keyboard shortcuts config

or

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf


## Editing and Navigation

|         en_US         |         fr_CA         | Description
| --------------------- | --------------------- | ------------------------------------------------------
| `Ctrl + \`            | `Ctrl + <`            | Split editor
| `Ctrl + Shift + P`    | `Ctrl + Shift + P`    | Command palette
| `F1`                  | `F1`                  | Command palette
| `Ctrl + P`            | `Ctrl + P`            | Quick Open (jump to any file by name)
| `Ctrl + G`            | `Ctrl + G`            | Go to line
| `Alt + ←/→`           | `Alt + ←/→`           | Go back/foward (history of commands)
| `Ctrl + Shift + \`    | `Ctrl + Shift + <`    | Go to the matching bracket
| `Ctrl + Shift + O`    | `Ctrl + Shift + O`    | Go to symbol in the current file
| `Ctrl + T`            | `Ctrl + T`            | Go to symbol across all file
| `Ctrl + Shift + E`    | `Ctrl + Shift + E`    | Open file explorer in the sidebar
| `Ctrl + B`            | `Ctrl + B`            | Toggle sidebar (close/open)
| `Ctrl + 0`            | `Ctrl + 0`            | Go to sidebar
| `Ctrl + 1`            | `Ctrl + 1`            | Go to main editor
| `Ctrl + W`            | `Ctrl + W`            | Close current tab
| `Shift + Alt + ←/→`   | `Shift + Alt + ←/→`   | Shrink/expand selection (code block)
| `Alt + ↑/↓`           | `Alt + ↑/↓`           | Move a line up/down
| `Ctrl + /`            | `Ctrl + é`            | Toggle line comment
| `F12`                 | `F12`                 | Go to definition of this symbol
| `Ctrl + F12`          | `Ctrl + F12`          | Go to implementations of this interface/extend
| `Shift + F12`         | `Shift + F12`         | Go to references (where that symbol is used)
| `Shift + Alt + i`     | `Shift + Alt + i`     | Add cursors to line end


* **Ctrl + Shift + M** — Problems panel (errors/warnings)
* **F12** — Go to Definition
* **Alt + F12** — Peek Definition
* **Ctrl + Shift + F10** — Go to References
* **Ctrl + Shift + F** — Search in workspace
* **Ctrl + F** — Search in file
* **F8 / Shift + F8** — Next/previous error or warning

## Code Editing

* **Alt + Up / Alt + Down** — Move the current line
* **Shift + Alt + Up/Down** — Duplicate line or selection
* **Ctrl + é** — Toggle line comment
* **Shift + Alt + A** — Toggle block comment
* **Ctrl + Space** — Trigger autocomplete
* **Alt + Click** — Multiple cursors
* **Ctrl + Alt + Up/Down** — Add cursor above/below
* **Ctrl + D** — Select next occurrence of word
* **Ctrl + Shift + L** — Select all occurrences of selected text
* **Ctrl + Shift + <** — Jump to matching bracket

## File and Editor Management

* **Ctrl + N** — New file
* **Ctrl + S** — Save
* **Ctrl + Shift + T** — Reopen closed editor
* **Ctrl + Shift + N** — New VS Code window
* **Ctrl + <** — Split editor

## Terminal and Debugging

* **Ctrl + `** — Toggle terminal
* **Ctrl + Shift + `** — New terminal
* **F5** — Start debugging
* **Shift + F5** — Stop debugging
* **F10** — Step over
* **F11** — Step into

## Integrated Git

* **Ctrl + Shift + G** — Source Control view
* **Ctrl + Enter** (inside SCM input box) — Commit
* **Ctrl + Shift + U** — Open Output panel

## UI and Tools

* **Ctrl + Shift + E** — Explorer view
* **Ctrl + Shift + D** — Debug view
* **Ctrl + Shift + X** — Extensions view
* **Ctrl + K Z** — Zen mode

# Advanced feature

## Quick open `CTRL + P`

Search for file by file name. It support fuzzy search and PascalCase search using only the upper cased letter.

By default it show you recently opened files including opened tab.

- `↵`        — Open the file and close **Quick open**
- `Ctrl + ↵` — Open the file to the side and close **Quick open**
- `→`        — Open the file and keep **Quick open** open

## Go to Line `CTRL + G`

- Format `:rownum:colnum`
- You can use nagative indexing to go to line at the end (-1 is the last line)
- You can add those code at the end of a file with **Quick open**
- If you don't press `↵` it only preview the location

## Go to symbol in the current file `CTRL + ⇧ + O`

- Format `@symbol`
- Everything that has meaning in a programming language is a symbol (class, variable, object, ...)
- Using ↑/↓ allow you to preview your symbol in the current file
- All symbols show up ordered by their position in the file but if you add `:` they are ordered by type
- You can use thise symbol with **Quick open**