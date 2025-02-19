# CSS !important Overuse

This repository demonstrates a common CSS issue: the overuse of the `!important` flag.  While it can seem like a quick fix for style conflicts, relying on `!important` frequently makes CSS harder to maintain and debug.  The `bug.css` file shows an example, and `bugSolution.css` provides a better approach.

## Problem

The `bug.css` file shows how using `!important` can override styles in unexpected ways and lead to difficult-to-trace issues in larger projects.

## Solution

The `bugSolution.css` file presents a more organized and maintainable solution.  Instead of using `!important`, it utilizes CSS specificity and a more structured approach to style prioritization.