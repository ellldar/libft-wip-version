# Libft - WIP Version

This is the version of my Libft library that I am going to be constantly modifying as I progress through the 42 curriculum.
It might end up being completely different compared to what was originally required in the `Libft Project`

## Additions to the Libft

In this part I will list and describe new functions that I have included in this library since the original **Libft Library**

* ### ft_lstpop

I have added the **`ft_lstpop`** function which just adds some more functionality to the original **`ft_lstdelone`** and **`ft_lstdel`** functions. It removes one element of the linked list **`t_list **elem`** and points the **next** pointer of the previous element to the one that follows the **elem**.
```c
void    ft_lstpop(t_list **alst, t_list **elem, void (*del)(void *, size_t));
```

* ### get_next_line

**`get_next_line()`** is a function that returns a line ending with a newline, read from a file descriptor
```c
int     get_next_line(const int fd, char **line)
```

* ### ft_atoi_base

**`ft_atoi_base()`** is a function that converts the string argument str (base N <= 16) to an integer (base 10) and returns it.
```c
int     ft_atoi_base(const char *str, int str_base)
```
