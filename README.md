# Personal implementation of preprocessor

A simple C project that implements basic preprocessor operations such as file inclusion, comment removal, and macro handling.

## Features

- **File Inclusion:** Handles local and system header files.
- **Comment Removal:** Removes single-line and multi-line comments.
- **Macro Handling:** Basic framework for processing `#define` directives (Work in Progress).
- **Modular Design:** Uses separate C files for different operations.

## Project Structure

- `preprocessor_main.c` – Main program.
- `file_inclusion.c` – Handles header file inclusion.
- `comment_removal_file.c` – Removes comments.
- `macro_handler.c` – Handles macro processing.
- `makefile_2` – Build configuration.

## Requirements

- GCC compiler
- Make

## Build

```bash
make
```

## Run

```bash
./mypreprocessor filename.c
```

The program generates an intermediate preprocessed `.i` file.
