Aim to achieve 100% test coverage. For `*.py` files, write unit tests in `test_*.py`.
For implementations that do not have a corresponding `test_*.py` file, add test code by referring to other tests.

1. Run `rye run pytest --cov=. --cov-report=term-missing` to get the current coverage.
2. Analyze and then add the test code that will most likely increase the coverage from the current state.
3. Measure the coverage again to confirm that the number has improved.

Repeat the test generation process until the user is satisfied.

TODO: List the settings when starting for the first time
