# gh-interpreter

Interpreter for Grey Hack.

Supports all functionality of MS and GS. It does not support `import_code` yet though.

Got a debugger as a feature as well.

# Install

Uses [greybel-js](https://github.com/ayecue/greybel-js) for transpiling.

1. Nightly: `greybel test-interpreter.src build --installer`
2. Copy installer files into GreyHack
3. Compile installer files to ingame binary (this will automatically create all the files)
4. Compile test-interpreter.src to ingame binary
