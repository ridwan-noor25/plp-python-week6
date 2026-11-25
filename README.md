# Week 6 Assignment: Safe Functions and Error Handling

## Files

- safe_tools.py: Contains three functions that handle division errors, invalid number conversions, and missing dictionary keys.

## Reflection

An if check cannot catch "abc" on its own because the problem occurs when Python tries to convert the text into an integer. The int() function raises a ValueError when the conversion fails, so try and except are needed to handle the error without crashing the program.