What are Type Annotations in Python?

Type annotations are optional comments that provide information about the expected data types of variables, function arguments, and return values.

While not enforced at runtime in standard Python, they offer several benefits:

Enhanced Readability: Code becomes more self-documenting, aiding understanding and reducing cognitive load.
Improved Maintainability: Explicit type hints make it easier to modify code without unintended consequences.
Potential for Static Type Checking (Optional): Certain tools can leverage annotations to detect potential type-related issues during development.
Why Use Type Annotations?

Clarity: Type annotations promote clear communication of variable and function behavior.
Error Detection: Static type checkers can identify some type mismatches early, saving time and effort.
Maintainability: Code is easier to understand and modify for both you and others.
Integration with Tools: Frameworks and IDEs can leverage type annotations for features like code completion and refactoring.
How to Use Type Annotations

Type annotations follow variable names or function arguments and return values, separated by a colon (:).
You can use built-in types like int, float, bool, str, or custom types defined elsewhere in your code.
Common Type Annotations:

Basic Types:
int: Integer numbers (e.g., 10, -5)
float: Floating-point numbers (e.g., 3.14, 1.2e-5)
bool: Boolean values (True or False)
str: String literals (e.g., "Hello, world!")
Collections:
list: Ordered, mutable lists (e.g., [1, 2, 3])
tuple: Ordered, immutable tuples (e.g., (1, "Alice", True))
set: Unordered collections of unique elements (e.g., {1, 2, 2})
dict: Key-value pairs (e.g., {"name": "Alice", "age": 30})
Other Types:
None: Represents the absence of a value
Any: Indicates any data type (use sparingly)
Custom types: Defined using classes or enums
