# Libft - My Own Library

Welcome to **Libft**, a library where I implemented common C standard library functions from scratch. This project is a collection of essential functions that handle memory, strings, and character manipulations. It's my way of learning and understanding the underlying workings of these functions.

## Description

Libft is a project where I created my own versions of some common functions found in the C standard library. By writing them myself, I gained a deeper understanding of how these functions work and how to use them in more complex programs. The library includes functions for memory manipulation, string handling, and character classification, all designed to replace or complement standard C functions.

## List of Functions

### Memory Functions

- **`memset`**: Fills a block of memory with a specific value.
- **`bzero`**: Sets a block of memory to zero.
- **`memcpy`**: Copies memory from one location to another.
- **`memccpy`**: Copies memory until a certain character is found.
- **`memmove`**: Moves memory from one location to another, handling overlapping regions.
- **`memchr`**: Searches for a character in a block of memory.
- **`memcmp`**: Compares two blocks of memory.

### String Functions

- **`strlen`**: Calculates the length of a string.
- **`strdup`**: Duplicates a string.
- **`strcpy`**: Copies a string.
- **`strncpy`**: Copies up to a specified number of characters from one string to another.
- **`strcat`**: Concatenates two strings.
- **`strncat`**: Concatenates a specified number of characters from one string to another.
- **`strlcat`**: Safely concatenates strings while ensuring the destination buffer is not overflowed.
- **`strchr`**: Finds the first occurrence of a character in a string.
- **`strrchr`**: Finds the last occurrence of a character in a string.
- **`strstr`**: Searches for a substring within a string.
- **`strnstr`**: Searches for a substring within a string up to a specified length.
- **`strcmp`**: Compares two strings.
- **`strncmp`**: Compares up to a specified number of characters of two strings.

### Character Functions

- **`atoi`**: Converts a string to an integer.
- **`isalpha`**: Checks if a character is alphabetic.
- **`isdigit`**: Checks if a character is a digit.
- **`isalnum`**: Checks if a character is alphanumeric.
- **`isascii`**: Checks if a character is an ASCII character.
- **`isprint`**: Checks if a character is printable.
- **`toupper`**: Converts a character to uppercase.
- **`tolower`**: Converts a character to lowercase.

## Usage

To use the functions from this library, simply include the appropriate header file in your project. You can compile and link the library into your projects to replace or extend standard C functions.

### Compilation

```bash
gcc -Wall -Wextra -Werror -c *.c
ar rcs libft.a *.o
