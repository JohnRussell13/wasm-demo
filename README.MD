https://emscripten.org/docs/getting_started/downloads.html

emcc fib.c -o fib.html -sEXPORTED_RUNTIME_METHODS=ccall,cwrap
python -m http.server 8080

https://marcoselvatici.github.io/WASM_tutorial/