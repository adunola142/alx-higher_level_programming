
n - Hello, World
## About
An introductory project on:
- How to use the Python interpreter
- How to print text and variables using `print`
- How to use strings
- Indexing and slicing in Python
- How to check your code with `PEP 8`
## Requirements
- Python 3.4
- pep8 1.7
## File Descriptions
### Mandatory
**[0-run](0-run)** - Write a Shell script that runs a Python script. The Python file name will be saved in the environment variable `$PYFILE`.

**[1-run_inline](1-run_inline)** - Write a Shell script that runs Python code. The Python code will be saved in the environment variable `$PYCODE`.

**[2-print.py](2-print.py)** - Write a Python script that prints exactly `"Programming is like building a multilingual puzzle`, followed by a new line.

**[3-print_number.py](3-print_number.py)** - Complete the [source code](https://github.com/holbertonschool/0x00.py/blob/master/3-print_number.py) in order to print the integer stored in the variable `number`, followed by `Battery street`, followed by a new line.
  * not allowed to cast the variable number into a string
  * code must be 3 lines long
  * have to use the [(new print formatting)](https://pyformat.info/#number)

**[4-print_float.py](4-print_float.py)** - Complete the [source code](https://github.com/holbertonschool/0x00.py/blob/master/4-print_float.py) in order to print the float stored in the variable `number` with a precision of 2 digits.
  * not allowed to cast `number` to a string
  * have to use the [(new print formatting)](https://pyformat.info/#number)

**[5-print_string.py](5-print_string.py)** - Complete the [source code](https://intranet.hbtn.io/rltoken/SsZaCpUT5-6nybzBeUkHyw) in order to print a string stored in the variable `str` three times, followed by a new line, followed by its first 9 characters and a new line.
  * not allowed to use any loops or conditional statements
  * program should be maximum 5 lines long

**[6-concat.py](6-concat.py)** - Complete the [source code](https://github.com/holbertonschool/0x00.py/blob/master/6-concat.py) in order to print `Welcome to Holberton School!`
  * not allowed to use any loops or conditional statements
  * have to use the variables str1 and str2 in your new line of code
  * program should be exactly 5 lines long

**[7-edges.py](7-edges.py)** - Complete the [source code](https://github.com/holbertonschool/0x00.py/blob/master/7-edges.py) such that:
  * `word_first_3` contains the first 3 letters of the variable `word`
  * `word_last_2` contains the last 2 letters of the variable `word`
  * `middle_word` contains the value of the variable `word` without the first and last letters
  * not allowed to use any loops or conditional statements
  * program should be exactly 8 lines long

**[8-concat_edges.py](8-concat_edges.py)** - Complete the [source code](https://github.com/holbertonschool/0x00.py/blob/master/8-concat_edges.py) in order to print `object-oriented programming with Python`, followed by a new line.
  * not allowed to use any loops or conditional statements
  * program should be exactly 5 lines long
  * not allowed to create new variables
  * not allowed to use string literals

**[9-easter_egg.py](9-easter_egg.py)** - Write a Python script that prints "The Zen of Python", by TimPeters, followed by a new line.
  * script should be maximum 98 characters long

### Advanced
**[100-write.py](100-write.py)** - Write a Python script that prints exactly `and that piece of art is useful - Dora Korpar, 2015-10-19`, followed by a new line.
  * Use the function `write` from the `sys` module
  * not allowed to use `print`
  * script should print to `stderr`
  * script should exit with the status code `1`

**[101-compile](101-compile)** - Write a script that compiles a Python script file. The Python file name will be stored in the environment variable `$PYFILE`. The output filename has to be `$PYFILEc` (ex: `export PYFILE=my_main.py` => output filename: `my_main.pyc`)

**[102-magic_calculation.py](102-magic_calculation.py)** - Write a Python function `def magic_calculation(a, b):` that does exactly the same as the following Python bytecode:
```
 3		0 LOAD_CONST               1 (98)
              	3 LOAD_FAST                0 (a)
              	6 LOAD_FAST                1 (b)
              	9 BINARY_POWER
             	10 BINARY_ADD
             	11 RETURN_VALUE
```
In this project, I began practicing using the interpreter, printing text
and variables, and indexing and slicing strings in Python.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files. Provided by Holberton School.

## Function Prototypes :floppy_disk:

Prototypes for functions written in this project:

| File                       | Prototype                             |
| -------------------------- | ------------------------------------- |
| `10-check_cycle.c`         | `int check_cycle(listint_t *list);`   |
| `102-magic_calculation.py` | `def magic_calculation(a, b):`        |

## Tasks :page_with_curl:

* **0. Run Python File**
  * [0-run](./0-run): Bash script that runs a Python script file saved
  in the environment variable `$PYFILE`.

* **1. Run inline**
  * [1-run_inline](./1-run_inline): Bash script that runs Python code saved in the
  environment variable `$PYCODE`.

* **2. Hello, print**
  * [2-print.py](./2-print.py): Python script that prints exactly `"Programming is
  like building a multilingual puzzle`, followed by a new line using the function `print`.

* **3. Print integer**
  * [3-print_number.py](./3-print_number.py): Python script that prints the integer stored
  in the variable `number`, followed by `Battery street`, followed by a new line.
  * Completion of [this source code](https://github.com/holbertonschool/0x00.py/blob/master/3-print_number.py).

* **4. Print float**
  * [4-print_float.py](./4-print_float.py): Python script that prints the float stored
  in the variable `number` with a precision of two digits.
  * Completion of [this source code](https://github.com/holbertonschool/0x00.py/blob/master/4-print_float.py).

* **5. Print string**
  * [5-print_string.py](./5-print_string.py): Python script that prints a string stored
  in the variable `str` three times, then a new line, then the first nine characters
  contained in `str`, followed by another new line.
  * Completion of [this source code](https://github.com/holbertonschool/0x00.py/blob/master/5-print_string.py).

* **6. Play with strings**
  * [6-concat.py](./6-concat.py): Python script that prints `Welcome to Holberton
  School!` using the variables `str1 = "Holberton"` and `str2 = "School"`.
  * Completion of [this source code](https://github.com/holbertonschool/0x00.py/blob/master/6-concat.py).

* **7. Copy - Cut - Paste**
  * [7-edges.py](./7-edges.py): Python script that sets three string variables based
  on the string contained in the variable `word` as follows:
  * `word_first_3`: Contains the first three letters of the variable `word`.
  * `word_last_2`: Contains the last two letters of the variable `word`.
  * `middle_word`: Contains the value of the variable `word` without the first and last letters.
  * Completion of [this source code](https://github.com/holbertonschool/0x00.py/blob/master/7-edges.py).

* **8. Create a new sentence**
  * [8-concat_edges.py](./8-concat_edges.py): Python script that prints `object-oriented
  programming with Python`, followed by a new line without creating new variables or
  string literals.
  * Completion of [this source code](https://github.com/holbertonschool/0x00.py/blob/master/8-concat_edges.py).

* **9. Easter Egg**
  * [9-easter_egg.py](./9-easter_egg.py): Python script that prints "The Zen of Python" by
  Tim Peters, followed by a new line.

* **10. Linked list cycle**
  * [10-check_cycle.c](./10-check_cycle.c): C function that checks if a linked list
  contains a cycle.
  * Returns `0` if there is no cycle and `1` if there is.
  * Helper files:
    * [linked_lists.c](./linked_lists.c): C functions handling linked lists for testing
    [10-check_cycle.c](./10-check_cycle.c) (provided by Holberton School).
    * [lists.h](./lists.h): Header file containing definitions and prototypes for
    all types and functions used in [linked_lists.c](./linked_lists.c) and
    [10-check_cycle.c](./10-check_cycle.c).

* **11. Hello, write**
  * [100-write.py](./100-write.py): Python script that prints exactly `and that piece of
  art is useful - Dora Korpar, 2015-10-19`, followed by a new line to `stderr` using
  the function `write` from the `sys` module.
  * Exits with a status code of `1`.

* **12. Compile**
  * [101-compile](./101-compile): Python script that compiles a Python script file stored
  in the environment variable `$PYFILE` and saves it to an output file
  `$PYFILEc` (ex. `export PYFILE=my_main.py` => output filename: `my_main.pyc`).

* **13. ByteCode -> Python #1**
  * [102-magic_calculation.py](./103-magic_calculation.py): Python function matching exactly
  a bytecode provided by Holberton School.

