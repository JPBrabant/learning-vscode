# Shortucts

`CTRL+K CTRL+S` — Open the keyboard shortcuts config

or

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf


## Editing and Navigation

|      en_US      |      fr_CA      | Description
| --------------- | --------------- | --------------------------------------
| `Ctrl + \`      | `Ctrl + <`      | Split editor
| `Ctrl + ⇧ + P`  | `Ctrl + ⇧ + P`  | Command palette
| `F1`            | `F1`            | Command palette
| `Ctrl + P`      | `Ctrl + P`      | Quick Open (jump to any file by name)
| `Ctrl + P`      | `Ctrl + P`      | Quick Open (jump to any file by name)
| `Ctrl + G`      | `Ctrl + G`      | Go to line

* **Ctrl + Shift + O** — Go to symbol in the current file
* **Ctrl + T** — Go to symbol across all files
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
* **Ctrl + W** — Close editor/tab
* **Ctrl + Shift + T** — Reopen closed editor
* **Ctrl + Shift + N** — New VS Code window
* **Ctrl + <** — Split editor
* **Ctrl + 1 / 2 / 3** — Focus editor group

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

* **Ctrl + B** — Toggle sidebar
* **Ctrl + Shift + E** — Explorer view
* **Ctrl + Shift + D** — Debug view
* **Ctrl + Shift + X** — Extensions view
* **Ctrl + K Z** — Zen mode

# Advanced feature

## Quick open `CTRL + P`

Search for file by file name. It support fuzzy search and PascalCase search using only the upper cased letter.

- `↵`        — Open the file and close **Quick open**
- `Ctrl + ↵` — Open the file to the side and close **Quick open**
- `→`        — Open the file and keep **Quick open** open

## GoTo Line `CTRL + G`

- `:12`    — You can enter a line number and you can use nagative indexing to go to line at the end (-1 is the last line)
- `:12:15` — You can enter a column number after the line number
