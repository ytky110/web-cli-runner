Written by ChatGPT.

Run C/C++ CLI with Wasm on web.

```bash
emcc main.c \
    -o cli.js \         # Need to be cli.js
    -s MODULARIZE=1 \
    -s EXPORT_ES6=1

em++ main.cpp \
    -o cli.js \         # Need to be cli.js
    -s MODULARIZE=1 \
    -s EXPORT_ES6=1
```
