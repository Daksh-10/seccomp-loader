Code Inspection
The structure of the code is clear, the function names suggest its purpose and makes it a readable code.

The code is modular and separated in different files based on the functionality of the task like reading header, filter and filtering.

Improvements:

1. It is always better to gracefully handle errors rather than panicing, so the UX doesn't break.
2. There should be tests, so including tests would help the user to understand the working of code and check for its robustness.
3. If something is must, then const should be used in order to access them across the code faster.
4. The files which opens should always be closed, so calling a destructor would be better using RAII pattern.
