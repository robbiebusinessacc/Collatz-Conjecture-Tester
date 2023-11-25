# Collatz Conjecture Tester

## Overview

This repository contains a Jupyter notebook that implements two methods for testing the Collatz conjecture, a famous problem in mathematics. The Collatz conjecture, also known as the 3n + 1 conjecture, posits that for any positive integer if the number is even, you divide it by two, and if it's odd, you triple it and add one. Repeating this process will always eventually reach the number 1.

The provided implementation tests this conjecture for a range of numbers starting from a very high value (295147905180464999992) using both a recursive and an iterative approach.

## Contents

- `collatz_conjecture_tester.ipynb`: A Jupyter notebook containing the Python code for testing the conjecture.

## Methods

The project implements the Collatz sequence calculation in two ways:

1. **Recursive Function with Memoization (`collatz_recursive`)**: This function uses recursion to calculate the sequence, employing memoization to optimize performance by caching the results of previous calculations.

2. **Iterative Function (`collatz_iterative`)**: An iterative approach to calculate the sequence, generally more memory-efficient.

## Usage

To run the notebook:

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed; if not, you can install it via Anaconda or with pip.
3. Open the `collatz_conjecture_tester.ipynb` notebook in Jupyter.
4. Run the cells sequentially to observe the implementation and tests of the Collatz conjecture.

## Requirements

- Python 3.x
- Jupyter Notebook
- tqdm (for progress bars in the notebook)

You can install the required packages using `pip`:

```bash
pip install notebook tqdm
```

## Performance

The notebook compares the execution times of the recursive and iterative approaches over a subset of the tested number range.

## Future Enhancements

Future updates to this project could include:

- Optimizing the algorithms further.
- Adding visualizations for the lengths of Collatz sequences.
- Extending the range of numbers tested.

## License

This project is open source and available under the [MIT License](LICENSE).
