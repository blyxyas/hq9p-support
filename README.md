# HQ9+ Support for VSCode

This is a simple extension for supporting the great HQ9+ programming language and its syntax. All characters other than H, Q, 9 and + are treated as comments.

If you're in a hurry, you can compile your new and blazingly fast with my [HQ9+ Compiler](https://github.com/blyxyas/hq9c)

The way to install it is by manually packaging the extension (because of Microsoft account system. I hate it.)

```
vsce package
```

And then you can use `CTRL + P` and write *"Install from VSIX"*, select the `.vsix` file and enjoy!