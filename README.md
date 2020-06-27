# Mathlingua Language Support

This is the official Visual Studio Code extension to provide language support for the [Mathlingua](https://www.mathlingua.org/) language.

## Features

Supports syntax highlighting, auto-analysis, autocomplete, and rendering of MathLingua documents (with a `.math` extension).  Any parse errors are displayed within the current file on save, and any signatures that are used, but have not been defined, are marked with a warning.

Furthermore, entering the `mathlingua` command at the command palette will manually open a preview window that renders the current MathLingua document.  In addition, when a `.math` file is opened, the preview window is automatically opened.

## Release Notes

### 0.7.2 (2020-06-26)
- The preview window is now automatically displayed when opening a `.math` file.

### 0.7.1 (2020-06-26)
- Rendered views preserve item order.
- Fixed an issue expanding "written as" forms.
- Improved font sizes.

### 0.7.0 (2020-06-25)
- Add support for rendering custom infix operators.  (For example render `x \set.in X` as `x \in X`).
- Left justify rendered html.

### 0.6.0 (2020-06-11)
- Add support for rendering MathLingua documents.

### 0.5.1 (2020-06-10)
- Update the README.

### 0.5.0 (2020-06-10)
- Updated to reflect changes to MathLingua where `Theorem` is used instead of `Result` and `Resource` is used instead of `Source`.

### 0.4.0 (2020-05-20)
- Warnings are displayed for signatures that are used but have not been defined.

### 0.3.0 (2020-05-19)
- Parse errors are now displayed within the editor on save.

### 0.2.0 (2020-05-18)
- Autocomplete of `Defines:` and `Represents:` signatures has been added but only within the current file.  That is, if a signature is specified in file `a.math`, then file `b.math` does not yet know about it.

### 0.1.1 (2020-05-17)
- Included more keywords to identify the extension

### 0.1.0 (2020-05-17)
- Introduced syntax highlighting support
- Introduced autocompletion for structural components (i.e. not statements within single quotes)
