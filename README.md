# Libft

Libft is a custom C library that contains commonly used functions and utility tools for programming in C. This library is designed to help developers save time by providing well-tested implementations of functions that are often used in various projects.

---

## Introduction

`Libft` is a collection of standard C functions and custom implementations designed to be used in projects that require utility functions such as string manipulation, memory allocation, character checks, and more. It serves as the foundation of many C projects, helping to standardize and optimize the development process.

---

## List of Functions

### String Functions
- `ft_strlen()`: Returns the length of a string.
- `ft_strdup()`: Duplicates a string by dynamically allocating memory.
- `ft_strcpy()`: Copies a string to another buffer.
- `ft_strcmp()`: Compares two strings lexicographically.

### Memory Functions
- `ft_memset()`: Fills memory with a specified value.
- `ft_memcpy()`: Copies memory from one location to another.
- `ft_memmove()`: Moves memory from one location to another, handling overlapping regions.

### Character Functions
- `ft_isdigit()`: Checks if a character is a digit.
- `ft_isalpha()`: Checks if a character is an alphabetic letter.
- `ft_isalnum()`: Checks if a character is alphanumeric.
- `ft_isascii()`: Checks if a character is within the ASCII range.

### List Functions
- `ft_lstnew()`: Creates a new list element.
- `ft_lstadd_front()`: Adds an element to the front of the list.
- `ft_lstsize()`: Returns the size of the list.
- `ft_lstlast()`: Returns the last element in the list.

### Other Utility Functions
- `ft_itoa()`: Converts an integer to a string.
- `ft_strjoin()`: Joins two strings into one.
- `ft_strtrim()`: Removes leading and trailing whitespace characters from a string.
- `ft_putchar_fd()`: Writes a character to a file descriptor.
- `ft_putstr_fd()`: Writes a string to a file descriptor.

*This list can be expanded based on your implementations.*

---

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/libft.git
    ```

2. Navigate to the library folder:

    ```bash
    cd libft
    ```

3. Compile the library using `make`:

    ```bash
    make
    ```

4. Link the `libft.a` static library to your project:

    ```bash
    gcc -o your_program your_program.c -L. -lft
    ```

---

## Installation

To install `libft` to your system or local project:

1. Compile the library using `make`:

    ```bash
    make
    ```

2. If you want to install it globally, you can run:

    ```bash
    sudo make install
    ```

   This will copy the compiled `libft.a` to your system's default library directory.


