# 11ty-demo

This demonstrates 11ty data cascade.

An array of dogs is defined in many places.
They are temporarily disabled by adding an "x" after the name
in order to experiment with the precedence order of data cascades.

The 11ty docs on data cascade say the next priority for getting a piece of data after the front matter in the template being render is its layout, if any.
But this does not seem to be the case.
In this project everything takes priority over data in the layout.

See `level1/level2/demo.md` which uses
the layout in `_includes/layout.njk`.
