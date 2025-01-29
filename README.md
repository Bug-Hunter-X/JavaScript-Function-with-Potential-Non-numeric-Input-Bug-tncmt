# JavaScript Function with Potential Non-numeric Input Bug

This repository demonstrates a common error in JavaScript functions: improper handling of non-numeric inputs. The `foo` function performs addition or subtraction depending on the value of the first argument. However, it does not validate the input types, making it vulnerable to errors if non-numeric values are passed.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version with input validation.

## Bug Description
The original code lacks input validation, leading to potential errors if non-numeric inputs are provided to the function. This could manifest as unexpected results or runtime errors.