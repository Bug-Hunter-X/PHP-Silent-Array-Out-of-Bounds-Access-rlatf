# PHP Silent Array Out-of-Bounds Access

This repository demonstrates a common, yet subtle, error in PHP: silent failure when accessing array elements outside their valid index range.  PHP does not throw an error for this, returning `null` instead.  This can lead to unexpected program behavior and make debugging considerably more difficult.

The `bug.php` file showcases the problem, while `bugSolution.php` provides a robust solution using checks to prevent this silent failure.

This silent error is often hard to catch and is a frequent source of unexpected program behavior. Always ensure proper bounds checking when accessing array elements in PHP.