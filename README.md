glift
=====

Go Lightweight Frontend


### Development

For depgen.py to work, you'll need to
  - install pegjs as a node module
    - e.g., `export PATH=${HOME}/path/to/pegjs/bin:${PATH}`
  - export a CLOSURE variable pointing to the closure compiler.
    - e.g., `export CLOSURE="java -jar /path/to/closure_compiler.jar"`

I realize this is a bit hacky.  Hopefully at some point this will be rewritten
to be more robust.
