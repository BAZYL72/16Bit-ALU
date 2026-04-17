# 16-Bit Arithmetic Logic Unit (ALU)

A comprehensive implementation of a 16-bit Arithmetic Logic Unit (ALU) built in Logisim, designed to perform arithmetic, logical, shift, code conversion, and advanced operations on 16-bit operands.

---

## Features

### Arithmetic Operations
- 16-bit Addition
- 16-bit Subtraction
- 16-bit Multiplication
- 16-bit Division
- Power Calculation
- Logarithm Base 2

### Logical Operations
- AND, OR, XOR, XNOR, NOT
- Bitwise Left Shift
- Bitwise Right Shift

### Special Operations
- Binary to Gray Code Conversion
- Gray to Binary Code Conversion
- Factorial Calculation (0–9)

---

## Components

| Category | File Name | Description |
|----------|-----------|-------------|
| Basic Arithmetic | `16BitAdder.circ` | 16-bit addition |
| Basic Arithmetic | `16BitSubractor.circ` | 16-bit subtraction |
| Basic Arithmetic | `16BitMultiplier.circ` | 16-bit multiplication |
| Basic Arithmetic | `Divisor_16bit.circ` | 16-bit division |
| Logical Units | `16BitAND.circ` | Bitwise AND operation |
| Logical Units | `16BitOR.circ` | Bitwise OR operation |
| Logical Units | `16BitXOR.circ` | Bitwise XOR operation |
| Logical Units | `16BitXNOR.circ` | Bitwise XNOR operation |
| Logical Units | `16BitNOT.circ` | Bitwise NOT operation |
| Shift Operations | `16Bit_BitwiseLeftShift.circ` | Left shift operation |
| Shift Operations | `16Bit_BitwiseRightShift.circ` | Right shift operation |
| Code Conversion | `16BitBinaryToGrey.circ` | Binary to Gray conversion |
| Code Conversion | `16BitGreyToBinary.circ` | Gray to Binary conversion |
| Advanced | `Power_16Bit.circ` | Power calculation |
| Advanced | `16Bit_Log2.circ` | Logarithm base 2 |
| Advanced | `Factorial_0to9.circ` | Factorial for numbers 0–9 |

> **Main Implementation:** The complete ALU is integrated in `FINAL.circ`, which links all individual components into a single functional unit.

---

## Project Structure

```
16-Bit-ALU/
├── FINAL.circ                      # Complete ALU implementation
├── 16BitAdder.circ                 # 16-bit addition
├── 16BitSubractor.circ             # 16-bit subtraction
├── 16BitMultiplier.circ            # 16-bit multiplication
├── Divisor_16bit.circ              # 16-bit division
├── 16BitAND.circ                   # AND operation
├── 16BitOR.circ                    # OR operation
├── 16BitXOR.circ                   # XOR operation
├── 16BitXNOR.circ                  # XNOR operation
├── 16BitNOT.circ                   # NOT operation
├── 16Bit_BitwiseLeftShift.circ     # Left shift
├── 16Bit_BitwiseRightShift.circ    # Right shift
├── 16BitBinaryToGrey.circ          # Binary to Gray conversion
├── 16BitGreyToBinary.circ          # Gray to Binary conversion
├── Power_16Bit.circ                # Power calculation
├── 16Bit_Log2.circ                 # Logarithm base 2
└── Factorial_0to9.circ             # Factorial calculation
```

---

## Usage

1. Open the desired circuit file in Logisim.
2. For the full ALU experience, open `FINAL.circ`.
3. Input the required operands into the input pins.
4. Select the desired operation using the control bits.
5. The result will be displayed in the output pins.

---

## Requirements

- [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution) (recommended) or Logisim Classic
- Basic understanding of digital logic design

---

## Contributing

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Authors

- **Bazyl Sheikh**
- **Arsalan Tahir**
- **Usyad Arsalan**

---

## Acknowledgments

- [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution) team for the development environment.
- The digital logic design community for inspiration and support.
