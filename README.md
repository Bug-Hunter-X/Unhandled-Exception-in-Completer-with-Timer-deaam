# Unhandled Exception in Completer with Timer

This repository demonstrates a scenario in Dart where an asynchronous operation using `Completer` and `Timer` might throw an exception.  The example showcases how to correctly handle such exceptions using `try-catch`.

The `bug.dart` file contains code that can throw an exception if the asynchronous operation fails. The `bugSolution.dart` file provides the corrected version with proper error handling.

This example highlights an edge case that developers might overlook, especially when dealing with asynchronous operations and potential errors in complex Dart applications.  Proper error handling is crucial for robust applications, and this example emphasizes that.