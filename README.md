# Uncommon HTML Bug: Space in ID

This repository demonstrates an uncommon bug in HTML related to using spaces in element IDs.  The `getElementById()` method in JavaScript does not work correctly when the ID contains spaces.

## Bug Description
The bug arises from attempting to access an HTML element using `document.getElementById()` with an ID that includes a space. This results in the element not being found, leading to errors or unexpected behavior.

## Solution
The solution is simple: avoid using spaces in element IDs. Use hyphens or camel case instead.

## How to reproduce
1. Open `bug.html` in a web browser.
2. Observe that the text in the div element is not changed by the JavaScript code.

## How to fix
1. Open `bugSolution.html` in a web browser.
2. Observe that the text in the div element is changed correctly.