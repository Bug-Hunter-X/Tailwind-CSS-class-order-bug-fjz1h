# Tailwind CSS Class Order Bug

This repository demonstrates an uncommon bug in Tailwind CSS where the order of classes can unexpectedly affect styling.  The issue arises when using classes that modify the same CSS properties (e.g., `width` and `max-width`) in a specific sequence.  Incorrect ordering may lead to unexpected visual results.

## Reproduction

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the unexpected rendering caused by class order in `bug.js`.

## Solution

The solution is described in `bugSolution.js` which demonstrates a way to correctly define the order of Tailwind classes or use alternative methods that ensure the expected styling is applied.  Understanding class precedence within Tailwind is key to avoiding this issue.