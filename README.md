# Uncommon HTML Bug: Incorrect Text Content Update

This repository demonstrates a subtle bug related to updating the text content of an HTML element.  The issue arises from directly modifying the `textContent` property without properly considering the existing HTML structure.

## Bug Description
The bug lies in how the JavaScript code attempts to update the text content of the div with id "myDiv".  It directly assigns new text to `textContent`, potentially overwriting existing HTML elements within the div. This is a common mistake that can be hard to track down.