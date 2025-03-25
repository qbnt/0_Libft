# Libft

Libft is a foundational project at 42 that introduces students to C programming by implementing their own standard C library. This custom library is designed to be reused throughout future projects.

## 🛠️ Project Overview

The goal is to recreate essential functions from the C standard library and add utility functions that make C development more manageable. This project is a great exercise in understanding memory management, pointers, and data manipulation.

## 📚 What’s Included

### Mandatory Part

- **Libc Functions** (re-implemented with `ft_` prefix):  
  `ft_strlen`, `ft_memcpy`, `ft_atoi`, `ft_isalpha`, `ft_toupper`, etc.

- **Additional Utility Functions**:  
  `ft_substr`, `ft_strjoin`, `ft_split`, `ft_itoa`, `ft_putchar_fd`, etc.

### Bonus Part (if mandatory part is flawless)

- **Linked List Handling**:  
  Create and manipulate singly linked lists with functions like `ft_lstnew`, `ft_lstadd_front`, `ft_lstmap`, etc.

## 🧪 How to Use

Clone the repository and run:

```bash
make
```

This will compile all necessary `.c` files and produce `libft.a`, your very own static library ready to be linked in future C projects.

## ✅ Compilation Flags

All files are compiled using:

```bash
-Wall -Wextra -Werror
```

## 📌 Notes

- No memory leaks are allowed.
- All code must conform to the 42 Norm.
- Only allowed functions are `malloc`, `free`, and `write` (depending on context).
