# FT_PRINTF

<p align="center">
  <img src="https://github.com/agathabarros/42-project-badges/blob/main/badges/ft_printfe.png"/>
</p>

## *Grade: 100 / 100*
`ft_printf` is a function that prints formatted strings based on given parameters. 
It supports conversions such as characters, strings, decimal and hexadecimal numbers, pointer addresses and percentages. 
The code is written in C and includes a Makefile and several helper functions from the C standard library and the libft library. 

`ft_printf` focuses on the concept of variadic functions, string parsing, and formatted output. This guide will cover all these topics as best as it can, and guide you through the main parts of the program.

## Installation

To get started, clone the repository and compile the project:

```bash
git clone https://github.com/agathabarros/42-ft_printf.git
cd ft_printf
make 
```

### Supported conversions - Mandatory

* `%c` print a character
* `%s` print a string
* `%d` and `%i` print a decimal number
* `%u` print an unsigned decimal number
* `%x` and `%X` print a hexadecimal number
* `%p` print a pointer address
* `%%` print a percent symbol
