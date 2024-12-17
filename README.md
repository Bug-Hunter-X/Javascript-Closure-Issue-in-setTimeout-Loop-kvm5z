This repository demonstrates a common closure issue in Javascript using the `setTimeout` function within a loop.  The example shows how the variable `i` is not captured properly, leading to unexpected behavior. A solution is provided which uses an Immediately Invoked Function Expression (IIFE) to create a separate scope for each iteration of the loop.