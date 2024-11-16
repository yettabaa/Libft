# Mark

This project was completed with a grade of 125/100 ✅ on October 26, 2022.

# libft
This project, Libft, is an essential part of the 42 curriculum, where the goal is to learn how fundamental C functions work by re-implementing them from scratch. By creating this custom library, you'll gain a deeper understanding of C programming and enhance your coding skills. Libft includes standard libc functions as well as other utility functions that will be used in future 42 projects. Through this process, you'll develop the knowledge and expertise to write clean, efficient code that you can rely on in your upcoming assignments. The project is designed to be a hands-on learning experience, encouraging trial and error, debugging, and thorough testing to ensure the correctness and efficiency of your functions.

# Requirement

In this project, you are allowed to use only three C standard library functions: [write()](https://man7.org/linux/man-pages/man2/write.2.html), [malloc()](https://man7.org/linux/man-pages/man3/malloc.3.html), and [free()](https://man7.org/linux/man-pages/man3/free.3p.html). However, you cannot use them freely; they are only permitted under specific conditions.
You need to compress them into a single archive for easy reuse in future projects.

This project is divided into three essential parts:

## Libc Functions

These functions already exist in C, so the requirement here is to recreate them to behave in the same way or as close as possible to the original functions from the C standard library.

| No  | Function Name     | Link                                                                 | No  | Function Name     | Link                                                                 |
| --- | ----------------- | ------------------------------------------------------------------- | --- | ----------------- | ------------------------------------------------------------------- |
| 1   | `ft_memset`       | [ft_memset](https://github.com/yettabaa/libft/blob/master/ft_memset.c)       | 13  | `ft_strnstr`      | [ft_strnstr](https://github.com/yettabaa/libft/blob/master/ft_strnstr.c)      |
| 2   | `ft_bzero`        | [ft_bzero](https://github.com/yettabaa/libft/blob/master/ft_bzero.c)         | 14  | `ft_strncmp`      | [ft_strncmp](https://github.com/yettabaa/libft/blob/master/ft_strncmp.c)      |
| 3   | `ft_memcpy`       | [ft_memcpy](https://github.com/yettabaa/libft/blob/master/ft_memcpy.c)       | 15  | `ft_atoi`         | [ft_atoi](https://github.com/yettabaa/libft/blob/master/ft_atoi.c)           |
| 4   | `ft_memccpy`      | [ft_memccpy](https://github.com/yettabaa/libft/blob/master/ft_memccpy.c)     | 16  | `ft_isalpha`      | [ft_isalpha](https://github.com/yettabaa/libft/blob/master/ft_isalpha.c)     |
| 5   | `ft_memmove`      | [ft_memmove](https://github.com/yettabaa/libft/blob/master/ft_memmove.c)     | 17  | `ft_isdigit`      | [ft_isdigit](https://github.com/yettabaa/libft/blob/master/ft_isdigit.c)     |
| 6   | `ft_memchr`       | [ft_memchr](https://github.com/yettabaa/libft/blob/master/ft_memchr.c)       | 18  | `ft_isalnum`      | [ft_isalnum](https://github.com/yettabaa/libft/blob/master/ft_isalnum.c)     |
| 7   | `ft_memcmp`       | [ft_memcmp](https://github.com/yettabaa/libft/blob/master/ft_memcmp.c)       | 19  | `ft_isascii`      | [ft_isascii](https://github.com/yettabaa/libft/blob/master/ft_isascii.c)     |
| 8   | `ft_strlen`       | [ft_strlen](https://github.com/yettabaa/libft/blob/master/ft_strlen.c)       | 20  | `ft_isprint`      | [ft_isprint](https://github.com/yettabaa/libft/blob/master/ft_isprint.c)     |
| 9   | `ft_strlcpy`      | [ft_strlcpy](https://github.com/yettabaa/libft/blob/master/ft_strlcpy.c)     | 21  | `ft_toupper`      | [ft_toupper](https://github.com/yettabaa/libft/blob/master/ft_toupper.c)     |
| 10  | `ft_strlcat`      | [ft_strlcat](https://github.com/yettabaa/libft/blob/master/ft_strlcat.c)     | 22  | `ft_tolower`      | [ft_tolower](https://github.com/yettabaa/libft/blob/master/ft_tolower.c)     |
| 11  | `ft_strchr`       | [ft_strchr](https://github.com/yettabaa/libft/blob/master/ft_strchr.c)       | 23  | `ft_calloc`       | [ft_calloc](https://github.com/yettabaa/libft/blob/master/ft_calloc.c)       |
| 12  | `ft_strrchr`      | [ft_strrchr](https://github.com/yettabaa/libft/blob/master/ft_strrchr.c)     | 24  | `ft_strdup`       | [ft_strdup](https://github.com/yettabaa/libft/blob/master/ft_strdup.c)       |

## Additional Functions
These functions do not exist in C (they may exist in other languages), so you need to create them to help you in future C projects. The challenge here is that the functions must not cause segmentation faults or memory leaks under any circumstances.

| No  | Function Name       | Link                                                                 | No  | Function Name       | Link                                                                 |
| --- | ------------------- | ------------------------------------------------------------------- | --- | ------------------- | ------------------------------------------------------------------- |
| 1   | `ft_substr`         | [ft_substr](https://github.com/yettabaa/libft/blob/master/ft_substr.c)         | 6   | `ft_strmapi`        | [ft_strmapi](https://github.com/yettabaa/libft/blob/master/ft_strmapi.c)        |
| 2   | `ft_strjoin`        | [ft_strjoin](https://github.com/yettabaa/libft/blob/master/ft_strjoin.c)       | 7   | `ft_putchar_fd`     | [ft_putchar_fd](https://github.com/yettabaa/libft/blob/master/ft_putchar_fd.c)  |
| 3   | `ft_strtrim`        | [ft_strtrim](https://github.com/yettabaa/libft/blob/master/ft_strtrim.c)       | 8   | `ft_putstr_fd`      | [ft_putstr_fd](https://github.com/yettabaa/libft/blob/master/ft_putstr_fd.c)    |
| 4   | `ft_split`          | [ft_split](https://github.com/yettabaa/libft/blob/master/ft_split.c)          | 9   | `ft_putendl_fd`     | [ft_putendl_fd](https://github.com/yettabaa/libft/blob/master/ft_putendl_fd.c)  |
| 5   | `ft_itoa`           | [ft_itoa](https://github.com/yettabaa/libft/blob/master/ft_itoa.c)            | 10  | `ft_putnbr_fd`      | [ft_putnbr_fd](https://github.com/yettabaa/libft/blob/master/ft_putnbr_fd.c)    |

## Bonus Functions
This part is not required to validate the project, but it is very important for exploring data structures, specifically singly linked lists. A linked list is a linear data structure where each element, called a node, is connected to the next one using pointers. Through this, you will learn how to create a linked list, delete a node, add a node at the front or back, and delete the entire linked list.
| No  | Function Name       | Link                                                                 | No  | Function Name       | Link                                                                 |
| --- | ------------------- | ------------------------------------------------------------------- | --- | ------------------- | ------------------------------------------------------------------- |
| 1   | `ft_lstnew`         | [ft_lstnew](https://github.com/yourusername/libft/blob/master/ft_lstnew.c)         | 6   | `ft_lstdelone`      | [ft_lstdelone](https://github.com/yourusername/libft/blob/master/ft_lstdelone.c)      |
| 2   | `ft_lstadd_front`   | [ft_lstadd_front](https://github.com/yourusername/libft/blob/master/ft_lstadd_front.c) | 7   | `ft_lstclear`       | [ft_lstclear](https://github.com/yourusername/libft/blob/master/ft_lstclear.c)       |
| 3   | `ft_lstsize`        | [ft_lstsize](https://github.com/yourusername/libft/blob/master/ft_lstsize.c)       | 8   | `ft_lstiter`        | [ft_lstiter](https://github.com/yourusername/libft/blob/master/ft_lstiter.c)        |
| 4   | `ft_lstlast`        | [ft_lstlast](https://github.com/yourusername/libft/blob/master/ft_lstlast.c)       | 9   | `ft_lstmap`         | [ft_lstmap](https://github.com/yourusername/libft/blob/master/ft_lstmap.c)         |
| 5   | `ft_lstadd_back`    | [ft_lstadd_back](https://github.com/yourusername/libft/blob/master/ft_lstadd_back.c) |
