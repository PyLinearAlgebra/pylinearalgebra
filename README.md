## pylinearalgebra

This is a Linear algebra package for performing arithmetic operations on matrices and matrix multiplication.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the pylinearalgebra library.

```bash
pip install pylinearalgebra
```

## Usage

```python
import pylinearalgebra as pg

# matrix multiplication
pg.matrix_multiplication(first_matrix = A, second_matrix = B)

# iterative solutions of linear systems
pg.iterative_solutions(coefficients_matrix = A, 
                       constants_vector = b, 
                       initial_guess = None, 
                       iterative_method = 'Jacobi', 
                       relaxation_parameter = None, 
                       matrix_method = True, 
                       tolerance = 1e-6, 
                       maximum_iterations = 10, 
                       decimal_points = 8)
# linear regression
pg.linear_regression(dependent_variable = y, 
                  independent_variables = x, 
                  slr_matrix = False, 
                  out_put = [], 
                  significance_level = 0.05, 
                  prediction = None, 
                  decimal_points = 8)
```

## Support

For any support and/or training on any of the functions in this package, send me an email at: pylinearalgebralibrary@cmstatistics2010@gmail.com.

## Roadmap

Future releases aim to make pylinearalgebra a for linear algebra

## Contributing

Contributing are welcome.

## Author and acknowledgement

I am grateful to the incredible support we got from everyone.

## License
[MIT](https://choosealicense.com/licenses/mit/)
