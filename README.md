Gradient Descent with Flexible Function Parsing and Evaluation
Overview

This project provides a flexible implementation of gradient descent optimization methods for arbitrary functions defined by mathematical expressions. It allows users to define and optimize functions with potentially n-variables using gradient-based optimization algorithms.

The core features of this project include:

    Parsing and evaluation of mathematical expressions using the ExprTk library.
    Implementation of various gradient descent optimization algorithms.
    Flexibility to define functions with arbitrary numbers of variables.

Dependencies

    Eigen library for linear algebra operations.
    ExprTk library for mathematical expression parsing and evaluation.

Compile the project running make from the directory of the repo.

Execution

Run the compiled executable with the desired mathematical expression and optimization algorithm:

bash

./main "y^2-x*3+x*y" 0

    The first argument is the mathematical expression.
    The second argument is the algorithm chosen to adjust the learning rate:
        0 for Armijo Learning Rate
        1 for Exponential Decay
        2 for Inverse Decay


Contributing

Contributions to this project are welcome! If you encounter any issues, have feature requests, or would like to contribute improvements, feel free to open an issue or submit a pull request.
License

This project is licensed under the MIT License.
