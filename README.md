# basic-antlr4
Basic Antlr4 Example

# Running
To run this example, first install dependencies with `poetry`:
```sh
poetry install
```
Then use poetry to run some commands (not sure if `antlr4` needs to be installed or not):
```sh
poetry shell
antlr4 -visitor -Dlanguage=Python3 Expr.g4
python Driver.py input.txt
```
The output should be something like:
```
-1.0
```
