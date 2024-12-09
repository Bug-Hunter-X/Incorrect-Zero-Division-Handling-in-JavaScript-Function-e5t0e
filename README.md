# Incorrect Zero Division Handling in JavaScript Function

This repository demonstrates a bug in a JavaScript function that incorrectly handles zero division. The function `foo` is designed to return 0 if either input `a` or `b` is 0; otherwise, it should return `a/b`. However, when either `a` or `b` is 0, it throws an error instead of returning 0 as intended.

The `bug.js` file contains the buggy code, and the `bugSolution.js` file provides a corrected version that addresses the zero division issue.