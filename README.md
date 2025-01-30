# Tailwind CSS @apply Directive Issue with Pseudo-Selectors

This repository demonstrates a bug where Tailwind CSS's `@apply` directive fails to apply styles correctly when used with pseudo-selectors like `:hover`, `:focus`, etc., especially in conjunction with other directives or complex class structures.  The issue arises from how `@apply` handles the merging and application of styles, particularly in the context of pseudo-selectors which are applied to states rather than base classes.

## Reproducing the Bug

1. Clone this repository.
2. Open `bug.css`.  You'll see an example of how `@apply` doesn't work as expected with the `:hover` pseudo-selector.
3. Observe the lack of hover effect as described in the bug description.
4. Examine `bugSolution.css` for a possible workaround.