# Libft - WIP Version

This is the version of my Libft library that I am going to be constantly modifying as I progress through the 42 curriculum.
It might end up being completely different compared to what was originally required in the `Libft Project`

## Additions to the Libft

This part will address the changes that I have included since I turned in the original **Libft Library**

* ### ft_lstpop

I have added the **`ft_lstpop`** function which just adds some more functionality to the original **`ft_lstdelone`** and **`ft_lstdel`** functions. It removes one element of the linked list **`t_list **elem`** and points the **next** pointer of the previous element to the one that follows the **elem**.
```
void  ft_lstpop(t_list **alst, t_list **elem, void (*del)(void *, size_t));
```

* ### get_next_line

**`get_next_line()`** is a function that returns a line ending with a newline, read from a file descriptor
```
int   get_next_line(const int fd, char **line)
```
