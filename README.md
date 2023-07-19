# ft_printf

This project is a rewrite of the printf function from the C standard library.

## How does it work?

Download/clone the repo:
  
  ```sh
  git clone https://github.com/startaglia/libft.git ft_printf
  cd ft_printf
  ```
It's a project written on Linux, to make it work on MAC you have to replace `intptr_t` with `uintptr_t` </br></br>
Now you need a text file for test it.
This is an example main for run and compile the program:

```
int	main(void)
{
  char	*line;
  int		i;
  int		fd1;
  
  fd1 = open("file.txt", O_RDONLY);
  i = 1;
  while (i < 7)
  {
    line = get_next_line(fd1);
    printf("line [%02d]: %s", i, line);
    free(line);
    i++;
  }
  close(fd1);
  return (0);
}
```
## Authors

### Simone Tartaglia -  startaglia89@gmail.com - <a href="https://github.com/startaglia" target="_blank"><img align="center" src="https://icon-library.com/images/github-icon-svg/github-icon-svg-0.jpg" height="30" width="30" /></a> <a href="https://www.linkedin.com/in/simone-tartaglia-134723248/" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/simone-tartaglia-134723248/" height="30" width="30" /></a>
