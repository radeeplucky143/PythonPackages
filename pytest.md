Pytest is a powerful testing framework for Python. Here are some of the most useful commands and options you might find helpful:

Running Tests:

pytest: Runs all tests in the current directory and subdirectories.
pytest <test_file.py>: Runs tests in a specific file.
pytest <directory>: Runs tests in a specific directory.
Selecting Tests:

pytest -k "expression": Runs tests that match the given expression.
pytest -m "marker": Runs tests that are marked with a specific marker.
Test Reporting:

pytest -v: Provides a verbose output.
pytest --maxfail=num: Stops after the first num failures.
pytest --tb=style: Changes the traceback style (e.g., short, long, line).
Test Discovery:

pytest --collect-only: Shows which tests would be run without actually running them.
Fixtures:

pytest --setup-show: Shows setup and teardown of fixtures.
pytest --fixtures: Lists all available fixtures.
Configuration:

pytest --disable-warnings: Disables warnings during test runs.
pytest --cache-clear: Clears the cache before running tests.
Debugging:

pytest --pdb: Enters the Python debugger on errors.
pytest --trace: Enters the Python debugger at the start of each test.
