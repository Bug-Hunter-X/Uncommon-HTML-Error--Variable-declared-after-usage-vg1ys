# Uncommon HTML Error: Variable declared after usage
This repository demonstrates an uncommon error in HTML that occurs when you use a variable in JavaScript code before it is declared. This can lead to unexpected behavior or errors depending on whether strict mode is enabled.
## Bug Description
The bug occurs within a script tag embedded within the HTML. It involves using a variable (myVar) before its declaration. In strict mode, this will throw a ReferenceError, indicating that the variable is not defined. However, in non-strict mode, the error might not be thrown explicitly, but the variable might have an unexpected value (undefined), potentially leading to subtle bugs in the application's logic.
## Bug Solution
The solution involves ensuring that variables are declared before they're used. This prevents any ambiguity regarding the variable's existence and its value, leading to cleaner and more predictable behavior.