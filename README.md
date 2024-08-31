Libft
Libft is a custom C library created as part of the 42 curriculum to provide implementations of various standard library functions, additional utilities, and data structures. This project aims to deepen understanding of how these functions work, improve C programming skills, and serve as a valuable tool for subsequent projects.

Table of Contents
Introduction
Common Instructions
Mandatory Part
Part 1 - Libc Functions
Part 2 - Additional Functions
Bonus Part
Installation
Usage
Testing
Contributing
License
Introduction
C programming can be challenging without access to standard functions. The Libft project is designed to create a custom library of these functions, enabling better control and understanding of their implementation. This library will be a valuable resource for future C assignments and projects within the curriculum.

Common Instructions
Language: C
Norm Compliance: Ensure all code complies with the 42 norm. Bonus functions must also adhere to these norms.
Memory Management: Properly manage and free all allocated memory. Memory leaks are not tolerated.
Makefile: Your Makefile should include rules for NAME, all, clean, fclean, and re. Use cc with -Wall, -Wextra, and -Werror flags.
Submission: Include Makefile, libft.h, and all ft_*.c files. Unused files must not be submitted.
Testing: Create and use test programs for validation, though they are not part of the submission.
Mandatory Part
Part 1 - Libc Functions
Implement the following functions with the ft_ prefix:

ft_isalpha()
ft_isdigit()
ft_isalnum()
ft_isascii()
ft_isprint()
ft_strlen()
ft_memset()
ft_bzero()
ft_memcpy()
ft_memmove()
ft_strlcpy()
ft_strlcat()
ft_toupper()
ft_tolower()
ft_strchr()
ft_strrchr()
ft_strncmp()
ft_memchr()
ft_memcmp()
ft_strnstr()
ft_atoi()
Use malloc() for:

ft_calloc()
ft_strdup()
Part 2 - Additional Functions
Implement the following additional functions:

ft_substr()
ft_strjoin()
ft_strtrim()
ft_split()
ft_itoa()
ft_strmapi()
ft_striteri()
ft_putchar_fd()
ft_putstr_fd()
ft_putendl_fd()
ft_putnbr_fd()
Bonus Part
If the mandatory part is perfect, implement the following functions for manipulating lists:

Add the following structure to libft.h:

c
Copy code
typedef struct s_list {
    void *content;
    struct s_list *next;
} t_list;
Implement the following functions:

ft_lstnew()
ft_lstadd_front()
ft_lstsize()
ft_lstlast()
ft_lstadd_back()
ft_lstdelone()
ft_lstclear()
ft_lstiter()
ft_lstmap()
Installation
To compile the library, run the following command in your terminal:

bash
Copy code
make
