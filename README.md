# Fastarithmetic

fastarithmetic is a Python package designed for fast and efficient arithmetic operations on very large numbers.
It implements optimized algorithms like Karatsuba multiplication and Newton-Raphson division to provide
significantly faster performance than Python's native arithmetic operators.

### Features
- **Fast Addition:** Performs addition of large numbers in O(1) time complexity.
- **Fast Subtraction:** Performs subtraction of large numbers in O(1) time complexity.
- **Optimized Multiplication:** Uses the Karatsuba algorithm (O(n^1.58)) for large integer multiplication.
- **High-Speed Division:** Implements the Newton-Raphson method (O(M(n))) for efficient division.

### Use Cases
- Scientific computations with extremely large integers.
- Cryptography where high precision and fast operations are required.
- Big data applications involving large-scale numerical processing.

### Installation
To install fastarithmetic, run the following command:

    pip install fastarithmetic

### Example Usage

    from fastarithmetic import fast_add, fast_sub, fast_mul, fast_div

    a = 987654321987654321987654321
    b = 123456789123456789

    print("Addition:", fast_add(a, b))
    print("Subtraction:", fast_sub(a, b))
    print("Multiplication:", fast_mul(a, b))
    print("Division:", fast_div(a, b))

### Performance Comparison
Compared to native Python arithmetic, fastarithmetic is optimized for large numbers and provides faster computation
for multiplication and division due to the use of advanced algorithms.
