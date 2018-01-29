# Checklist

Below is a checklist to reference when configuring an editor for a new
language. This is intended for personal use and is obviously subject to a lot
of opinions.

## Non-negotiables

* Up-to-date syntax highlighting
* Reliable stdlib autocompletion
* Display linting and error messages - via [flycheck] or something similar
* Goto definition - file and project-wide source code jumping
* Jump to tests - find or create test files for a given module
* Snippets - function definitions, variable definitions, conditionals,
	imports, etc
* Vim-like text objects - function definitions, comment blocks, etc

## Nice to haves

* Find references via xref
* REPL access
* Autocompletion for popular libraries or ideally via Microsoft's Language
	Server Protocol
* Documentation browsing - ideally via `K` in vim-like environments
* Support for jumping to the standard library's source code
  
[flycheck]: http://www.flycheck.org/en/latest/
