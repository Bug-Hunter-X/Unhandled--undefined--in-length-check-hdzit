# Unhandled 'undefined' in length check

This JavaScript code demonstrates a common error: failing to handle the case where a variable might be undefined before accessing its properties.  The `foo` function is intended to return the length of an array, or 0 if the input is null. However, it crashes if the input is undefined because `undefined.length` throws an error.

The solution shows how to add a check for undefined to prevent this crash. 