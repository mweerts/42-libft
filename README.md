_This project has been created as part of the 42 curriculum by maxweert (GitHub: mweerts)._

# libft

## Description

Libft is a custom C library developed as part of the 42 Common Core.

The goal of the project is to build a reusable C utility library while exploring fundamental concepts such as memory management, pointer arithmetic, string manipulation and data structures.

### Library Contents

- Character classification and conversion
- String manipulation
- Memory management
- Numeric conversions
- File descriptor output
- Singly linked list utilities (bonus)

## Instructions

### Build

```bash
make
```

### Clean

```bash
make clean
make fclean
```

### Usage

```c
#include "libft.h"
```

Link against the generated library:

```bash
cc main.c -L. -lft
```

## Resources

Linux man pages

### AI Usage

AI assistance was limited to the creation of this README and project documentation.

The project implementation was completed without AI-generated code.

## Status

**Final Grade: 125/100**

- Mandatory part completed
- Bonus part completed
