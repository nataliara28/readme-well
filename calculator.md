# 🧮 My Calculator Project 🧮

Welcome to **My Calculator** - a simple yet functional calculator project written in Python! This is my first project where I've implemented basic arithmetic operations with a twist of integer division.

## 📜 Project Overview

This calculator supports the following features:

- **Basic Arithmetic Operations**: Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
- **Integer Division**: The special operator `~` is used for integer division. It not only provides the quotient but also the remainder.
- **Multi-digit Numbers**: The calculator can handle operations involving multi-digit numbers.

### 📝 Assumptions

- **Input Validation**: The calculator assumes that all inputs are valid. Therefore, no input validation is implemented.
- **No Spaces**: Inputs should not contain spaces between numbers and operators.

## ⚙️ How It Works

The calculator reads the desired number of operations from the user and processes each one sequentially. For each operation:

1. The operator is identified.
2. The input string is split into operands.
3. The operation is performed based on the operator provided.

### Example Operations:

- Addition: `3+5` → Output: `The answer is 8`
- Subtraction: `10-2` → Output: `The answer is 8`
- Multiplication: `4*7` → Output: `The answer is 28`
- Division: `8/2` → Output: `The answer is 4.0`
- Integer Division: `9~4` → Output: `The answer is 2. The remainder is 1`

## 🛠️ Code Explanation

Here's a breakdown of the key functions in the code:

### `get_operator(operation)`

- **Purpose**: Extracts and returns the first operator found in the input string.
- **Input**: A string representing the operation (e.g., `"9+3"`).
- **Output**: The operator (e.g., `"+"`).

### `calculate(operation)`

- **Purpose**: Performs the calculation based on the provided operation.
- **Input**: A string representing the operation (e.g., `"9+3"`).
- **Output**: Prints the result directly to the console.

### `main()`

- **Purpose**: The main function of the calculator, managing the flow of user input and calculation processing.
- **Functionality**:
- Greets the user.
- Asks for the number of calculations to perform.
- Iterates through each calculation and calls the `calculate()` function.

## 🚀 Getting Started

To run the calculator on your local machine:

1. **Clone the repository** (if applicable) or copy the script into your local environment.
2. **Run the script** using Python:

```bash
python calculator.py
```

3. Follow the prompts to enter the number of calculations and the operations.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#) for more information.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

[Ading a license to a repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)

## 🙏 Acknowledgements

Thanks for checking out my first project! Any feedback or suggestions are greatly appreciated.

---

Made with ❤️ by Natalia Rico
