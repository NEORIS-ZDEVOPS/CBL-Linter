# CBL Linter Extension for z/OS

**CBL Linter Extension for z/OS. It's an extension for Visual Studio Code that provides a cobol language server to improve COBOL code quality.**

This extension is designed to assist developers with code in COBOL by highlighting and warning about potential errors in the code and suggesting quick-fix actions.

## Features

The rules that this extension offer to highlight are:
- The name of the program must be the same than the file name.
- EXEC instructions must have it END instruction.
- There are some COBOL instructions that are prohibited in certains enviroments (CANCEL, ACCEPT).
- Check that every variable declared in working storage section are used in the program.

## Requirements

N/A

## Known Issues

Issues can be checked in the [issue tracker](https://github.com/NEORIS-ZDEVOPS/CBL-Linter/issues)

## How to use

Check the documentation in [our github page](https://github.com/NEORIS-ZDEVOPS/CBL-Linter/tree/master/doc)
