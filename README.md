# Binary Calculator — Step by Step

A web-based binary calculator that shows paper-style step-by-step operations for addition, subtraction, and multiplication.

---

## Features

- Addition with carry display
- Subtraction with borrow display (larger number on top)
- Multiplication with partial products (paper layout)
- Step-by-step output for each bit operation
- Works with any binary numbers entered by the user
- No external dependencies

---

## How to Use

1. Enter two binary numbers (only 0 and 1)
2. Select an operation: ADD, SUB, or MUL
3. Click CALCULATE
4. View the step-by-step process and the final result

---

## Output Format

Addition:

    bitA + bitB = result (carry N)
    bitA + bitB + carry = result (carry N)
    carry final = N
    RESULT = binary

Subtraction:

    bitA - bitB = result (borrow 1)
    bitA - bitB - borrow = result
    RESULT = binary

Multiplication:

    A × bit = partial
    A × bit = partial

          A
    ×     B
    ---------
      partials
    ---------
        result

    RESULT = binary

---

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript

---

## File Structure

    binary-calculator/
    ├── index.html
    └── README.md

Open index.html in any modern browser. No installation required.

---

## Notes

- Subtraction assumes the first number (A) is greater than or equal to the second (B)
- All numbers are treated as positive integers
- Single-file application

---

## License

MIT License
