# Libft Library
## Overview
- The Libft library serves as a foundational toolset within the realm of C programming, providing a comprehensive suite of custom functions that complement the standard C library.

## Objective
- Create a static library containing essential C functions, including those found in string.h and stdlib.h.

## Usage
To use the Libft library in your projects, follow these steps:

1. Clone the repository:
```
git clone <repository-url>
```
2. Navigate to the libft directory:
```
cd ft_libft
```
3. Compile the library:
```
make
```
4. Include the libft.h header file in your source code.
```
#include "libft.h"
```
5. Link your program with the libft.a library during compilation:
```
gcc -o my_program my_program.c -L. -lft
```
6. Execute your program:
```
./my_program
```
