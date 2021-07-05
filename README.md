# compiler-libs-opttoplevel

This opam packages only install META files for OCaml's native toplevel, assuming
your ocaml installation does ship `ocamlopttoplevel.cmxa`. This will allow you
to use the native toplevel library in your dune projects.

To install in your current switch, simply run:
```
opam pin add compiler-libs-opttoplevel.0.1.0 git+https://github.com/NathanReb/compiler-libs-opttoplevel.git#0.1.0
```

or add the following `pin-depends` field to your opam file:
```
pin-depends: [
  [
    "compiler-libs-opttoplevel.0.1.0"
    "git+https://github.com/NathanReb/compiler-libs-opttoplevel.git#0.1.0"
  ]
]
```

The native toplevel library will be available under the name `compiler-libs-opttoplevel`.
