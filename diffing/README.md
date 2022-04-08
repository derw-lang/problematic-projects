# Problem

Diffing of nodes would sometime keep attributes from older versions of the DOM.

# Solution

Make sure to remove old attributes when patching facts. Fixed in [Coed 0.0.10](https://github.com/eeue56/coed/commit/1b4de509602c5cd09de81f89124003d6ff43981d)