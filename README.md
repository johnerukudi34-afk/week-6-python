# PLP Python Week 6 - Safe Functions

`safe_tools.py` contains three safe functions that handle division by zero, invalid number input, and missing dictionary fields using `try` and `except`.

`try` and `except` allow the program to catch specific errors and continue running instead of crashing.

An `if` check cannot catch `abc` on its own because `abc` is text, and converting it with `int()` causes a `ValueError`. The conversion must be placed inside `try` so the error can be caught and handled.
