# Passthword

A simple password manager with a slight lisp.

## Installation

Installation alternatives:

- Download passthword.el and drop it somewhere in your `load-path`.
- If you have melpa configured it's available through `package-install`.

# Usage

Issue `C-u M-x passthword` to interactively add your first password,
press `C-SPC` when prompted for password to insert a random generated
one.

Issue `M-x passthword` to select a password, the username will be
briefly shown through 'message and the password copied for you to
yank.

You can also delete a password through `M-x passthword-delete`.
