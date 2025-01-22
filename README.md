# Uncommon Tailwind CSS Bugs

This repository demonstrates some uncommon bugs and solutions in Tailwind CSS.  These issues are less frequent than the common configuration problems, but can be significantly harder to debug.

**Bugs Covered:**

*   **`@apply` Directive Issues:** Demonstrates problems that can arise from misusing Tailwind's `@apply` directive, including conflicts and unexpected style omissions.
*   **Purge Configuration Issues:** Shows issues related to the `purge` (or `content`) options in `tailwind.config.js`, leading to styles being unintentionally removed.
*   **CSS Conflicts:** Addresses situations where conflicting CSS rules interfere with Tailwind's styling, resulting in unexpected visual behavior.

**Solutions:**

The `bugSolution.js` file provides solutions and workarounds for the issues demonstrated in `bug.js`.

**How to reproduce:**

1.  Clone this repository.
2.  Install the required dependencies (if any).
3.  Run the provided code examples to observe the problematic behavior and then consult the solution file to see how to correct the issues.