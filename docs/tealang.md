# TeaLang Grammar Specification

## Program Grammar
TeaLang allows interleaved `use` statements and elements. This means you can mix `use` statements at various points within your code, enhancing modularity and readability.

## Array Initialization
Arrays can be initialized using square brackets, making it straightforward to create and populate collections of data. For example:

```tealang
myArray = [1, 2, 3, 4]
```

## Variable Declarations
Variable declarations in TeaLang are reorganized into specific categories:
- `scalar_decl`: For declaring single scalar variables.
- `typed_scalar_decl`: For declaring single scalar variables with a specified type.
- `array_decl`: For declaring arrays without specifying their types directly.
- `typed_array_decl`: For declaring arrays with specified types for their elements.
- `slice_decl`: For declaring slices, which are views on arrays.

## Reference Syntax for Function Calls
Function calls in TeaLang utilize a clear reference syntax, allowing for straightforward access to functions and their parameters. For example:

```tealang
result = myFunction(param1, param2)
``` 

This structure helps maintain clarity and ease of understanding while coding in TeaLang.### Additional Notes
Ensure to follow these specifications when writing TeaLang code to take full advantage of the language's features.