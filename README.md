# Tailwind CSS @apply Directive Bug
This repository demonstrates an uncommon bug encountered when using the `@apply` directive in Tailwind CSS with complex selectors.  The bug manifests as unexpected styling behavior, where the expected styles are not applied correctly.

## Bug Description
The `@apply` directive, when used with selectors containing pseudo-classes (e.g., `:hover`, `:focus`) and other modifiers, may fail to apply the intended styles in certain scenarios. This behavior is not consistently reproducible and appears to be related to the complexity of the selector involved.

## Reproduction Steps
1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the application (instructions may vary depending on your setup).
4. Observe the unexpected styling inconsistencies as described in the bug report.

## Solution
The solution involves refactoring the CSS to avoid the complex selectors that trigger the bug.  Alternative approaches using direct class application or a more streamlined CSS structure can resolve the issue. See `bugSolution.js` for a possible fix.
