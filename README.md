# Lexical Analyzer 

## Description
This Python program serves as a lexical analyzer, designed to read and analyze tokens from a given input file. It recognizes keywords, integers, floats, identifiers, and different types of operators. Identified tokens are either directly categorized or added to a symbol table for further reference. The analyzer is particularly useful in the initial phases of compilers and interpreters, where token recognition is crucial.

## Features
- **Token Recognition:** Identifies different types of tokens including keywords, integers, floats, and identifiers.
- **Symbol Table Integration:** Adds and retrieves identifiers from a symbol table.
- **Error Handling:** Detects and reports unrecognized strings as errors.
- **Interactive Menu:** Provides an interactive command line menu to process tokens, display the symbol table, or exit the program.

## Setup and Execution
### Prerequisites
- Python 3.x installed on your system.
- Basic understanding of Python programming and text file operations.

### Installation
No external libraries are required to run this program, as it solely utilizes Python’s built-in modules such as datetime and standard file handling.

### Running the Program
1. Save the Python script to a file, for example, `lexical_analyzer.py`.
2. Place the input file named `input.txt` in the same directory as the script.
3. Open your command line interface (CLI).
4. Navigate to the directory where the script is saved.
5. Run the script using Python:
    ```bash
    python lexical_analyzer.py
    ```

## Usage
Upon running the program, you'll be greeted with an interactive menu:
1. Enter 1 to process the next token from the file.
2. Enter 2 to display the current contents of the symbol table.
3. Enter 3 to exit the program.
The analyzer will read from the input file `input.txt`, and you can interact with the system through the menu to analyze tokens, inspect the symbol table, or stop the execution.

## File Format
The input file should contain text with tokens separated by spaces or new lines. Example content for `input.txt`:
