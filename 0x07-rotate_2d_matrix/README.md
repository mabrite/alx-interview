# 0x07-rotate_2d_matrix

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Getting Started](#getting-started)
4. [Usage](#usage)
5. [Testing](#testing)
6. [License](#license)

## Introduction

The `0x07-rotate_2d_matrix` project focuses on implementing an algorithm to rotate a 2D matrix by 90 degrees in place. This project is designed to help you understand matrix manipulation and in-place algorithms, which are common in technical interviews and coding challenges.

## Project Structure

The project directory contains the following files:

```
0x07-rotate_2d_matrix/
├── 0-rotate_2d_matrix.py
├── main.py
├── README.md
└── tests/
    └── test_rotate_2d_matrix.py
```

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/0x07-rotate_2d_matrix.git
```

2. Navigate to the project directory:

```bash
cd 0x07-rotate_2d_matrix
```

3. Install any required packages (if necessary, usually listed in `requirements.txt`):

```bash
pip install -r requirements.txt
```

## Usage

To rotate a 2D matrix by 90 degrees in place, you can use the `rotate_2d_matrix` function provided in `0-rotate_2d_matrix.py`.

### Example

```python
from 0_rotate_2d_matrix import rotate_2d_matrix

matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

rotate_2d_matrix(matrix)

print(matrix)
```

Output:
```
[
    [7, 4, 1],
    [8, 5, 2],
    [9, 6, 3]
]
```

## Testing

To run the tests, execute the following command:

```bash
python -m unittest discover tests/
```

This will run all tests in the `tests` directory.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
