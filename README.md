# Bug Report: Tailwind CSS @apply Directive and Pseudo-selectors

This repository demonstrates a bug related to the `@apply` directive in Tailwind CSS when used with pseudo-selectors such as `:hover`.  When nested within components or applied conditionally, the expected styles might not apply correctly.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies (if any).
3. Open `index.html` in your browser.
4. Observe the unexpected behavior of hover styles.

## Expected Behavior

The hover styles should apply correctly in all scenarios, regardless of nesting or conditional rendering.

## Actual Behavior

Hover styles are not applied as expected, resulting in inconsistent styling across different elements.

## Solution

The solution involves refactoring the usage of `@apply` and potentially using `@layer` or other techniques to manage conflicting styles.  See `bugSolution.html` for more details.