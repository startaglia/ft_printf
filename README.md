# ft_printf

This project is a rewrite of the printf function from the C standard library.

## Installing and running the project:

1- Clone the repo:
  
  ```sh
  git clone https://github.com/startaglia/ft_printf ft_printf
  ```

2- Enter in ft_printf dir and compile the program with the `make` command
	
 ```
 cd ft_printf
 make
 ```

### Makefile Available Targets:  
`make` or `make all` - Makes exe file 
`make clean` - Deletes all the resulting object files  
`make fclean` - Deletes the executables and all the resulting object files  
`make re` - fclean + all  
</br></br>

It's a project written on Linux, to make it work on MAC you have to replace `intptr_t` with `uintptr_t` </br></br>
Now you have your printflib ready to use!

## Technologies Used:

- **Programming Language**: C
- **Operating System**: Linux
- **Compiler**: GCC (GNU Compiler Collection)
- **Build System**: GNU Make
- **C Standard Library**
- **Variadic Functions**: Handling variable-length argument lists with `stdarg.h`
- **Command Line Arguments Handling**: Techniques such as `argc`/`argv`



## Authors:

- **Simone Tartaglia**
  - Email: [startaglia89@gmail.com](mailto:startaglia89@gmail.com)
  - GitHub: [startaglia](https://github.com/startaglia)
  - LinkedIn: [Simone Tartaglia](https://www.linkedin.com/in/simone-tartaglia-134723248/)
