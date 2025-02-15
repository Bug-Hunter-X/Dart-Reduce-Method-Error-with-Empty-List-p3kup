# Dart Reduce Method and Empty Lists

This example demonstrates a common error encountered when using the `reduce` method in Dart with an empty list. The `reduce` method requires at least one element; otherwise, it throws a `StateError`.  The solution involves adding a check for an empty list before using `reduce`.