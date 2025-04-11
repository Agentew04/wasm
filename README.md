# Web Assembly

* Skip the interpreting part of JS, run while downloading the file
* Binaries are already optimized, no need for optimizations on the V8(and others)
  * JIT can only optimize small amounts of code (hot path)
* Normally, webpages don't have really a hot path, only many smalls functions, ie. React
* Using existing libraries on the browser
* Running a Wasm runtime as a sandbox for plugins/addons.
  * Plugins can be written in any language and be restricted to specific services/APIs
* Port existing applications to the web
* Faster than JS on resource intensive tasks
* With WASI (WebAssembly System Interface), we can run wasm code directly on the computer, without the need of a browser
* Wasmer has WAPM, a complete package manager for wasm programs
* wasm and wasi use is encouraged by the Bytecode Alliance
