# A minimal js-of-caml project

This project is based on [this blog post](https://o1-labs.github.io/ocamlbyexample/libraries-js_of_ocaml.html), but it has been updated for the newest dune and core.

To build, run:

```
dune build ./main.bc.js
```

This generates a javascript file in `_build` that you can load and run:

```
node -e 'const m = require("./_build/default/main.bc.js").myLib; console.log(m.myVal);'
0
```


