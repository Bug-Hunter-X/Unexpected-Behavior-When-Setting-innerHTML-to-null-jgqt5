# Uncommon HTML Bug: Unexpected Behavior When Setting innerHTML to null

This repository demonstrates an uncommon bug related to setting the `innerHTML` property of an HTML element to `null`. While it might seem intuitive to use `null` to clear content, it can lead to unexpected behavior and inconsistencies across different browsers.

The bug is demonstrated in `bug.html`. The solution, which uses an empty string instead of `null`, is provided in `bugSolution.html`.