#Summary

* [Chapter 1 Getting started with Emscripten](ch1-quick-guide/readme.md)
  * [1.1 Installing Emscripten](ch1-quick-guide/ch1-01-install.md)
  * [1.2 Hello, world!](ch1-quick-guide/ch1-02-helloworld.md)
  * [1.3 Taking a look at the Emscripten glue code](ch1-quick-guide/ch1-03-glue-code.md)
  * [1.4 Selecting compilation target](ch1-quick-guide/ch1-04-compile.md)

* [Chapter 2 Connecting C and JavaScript](ch2-c-js/readme.md)
  * [2.1 Calling compiled C functions from JavaScript](ch2-c-js/ch2-01-js-call-c.md)
  * [2.2 Implement C API in JavaScript](ch2-c-js/ch2-02-implement-c-api-in-js.md)
  * [2.3 Memory model](ch2-c-js/ch2-03-mem-model.md)
  * [2.4 Exchange data between C and JavaScript](ch2-c-js/ch2-04-data-exchange.md)
  * [2.5 Using `EM_ASM`](ch2-c-js/ch2-05-em-asm.md)
  * [2.6 Using `emscripten_run_script`](ch2-c-js/ch2-06-run-script.md)
  * [2.7 Using `ccall`/`cwrap`](ch2-c-js/ch2-07-ccall-cwrap.md)
  * [2.8 Supplement](ch2-c-js/ch2-08-ext.md)

* Chapter 3 Emscripten runtime
  * 3.1 Runtime lifecycle
  * 3.2 Message loop
  * 3.3 File system
  * 3.4 Memory management
  * 3.5 Customize Module object
  * 3.6 Summary

* Chapter 4 General techniques that WebAssembly friendly
  * 4.1 Message loop detaching
  * 4.2 Memory alignment
  * 4.3 Exporting C++ objects using the C interface
  * 4.4 Lifecycle control for C++ object
  * 4.5 Importing JavaScript object using C interface
  * 4.6 Be careful with `int64`
  * 4.7 Forget about filesystem

* Chapter 5 Network IO
  * 5.1 XMLHttpRequest
  * 5.2 WebSocket

* Chapter 6 Multithreading
  * 6.1 Multithreading in JavaScript
  * 6.2 Using Emscripten in WebWorker

* Chapter 7 GUI
  * 7.1 canvas
  * 7.2 Mouse event
  * 7.3 Keyboard event
  * 7.4 Life