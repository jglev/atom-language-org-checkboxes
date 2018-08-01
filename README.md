# org-checkbox-coloring package

Adds coloring for checkboxes to org-mode in comments and text in Atom.

Checkbox coloring:

`- []`, `- [ ]`: Todo
`- [X]`, `- [x]`: Done
`- [>]`: Next / Scheduled
`- [<]`: Migrated
`- [/]`: Right now / In progress
`- [O]`, `- [0]`, `- [o]`: Waiting on someone else

Also includes syntax highlighting for org-mode.

Set the language for the document as `Org + Checkboxes`.

Based on Dmitriy Kiyatkin's [language-todo-extra-words](https://github.com/dkiyatkin/atom-language-todo-extra-words).

To install this locally, run `apm link` in the command line from this project's directory. If you then run `atom -d` (for development mode), after each `apm link`, you can use `Ctrl + Shift + P` and then select `Dev Live Reload: Reload All` to see your changes reflected.
