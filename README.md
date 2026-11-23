# Calculator
A Python 3 calculator used from the Terminal, built step by step in SCCM4910.
## What it will do
Add, subtract, multiply and divide two numbers; display the result.
## How to run it
Run: python3 calculator.py
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

## Running the calculator

Python 3 is required.

Run the calculator using:

./run.sh

Example test:
First number: 6
Operator: *
Second number: 7
Expected result: Result: 42.0

Press Ctrl+C to stop the calculator.

## Testing the calculator

Python 3 is required.

The testing dependency is pytest, listed in requirements-dev.txt.

Activate the SCCM4910 environment:

source /opt/python-venv/sccm-4910/bin/activate

Run the quality gate:

./check.sh

Expected result: 5 passed and QUALITY GATE PASSED.

Exit status 0 means all tests passed.
A non-zero exit status means the quality gate failed.

Check the exit status immediately after running:

echo $?

The existing ./run.sh command can still be used
to run the calculator.
