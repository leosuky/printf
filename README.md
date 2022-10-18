# _printf

```_printf``` is a custom implementation of the C programming function ```printf```.



**Prototype:** ```int _printf(const char *, ...);```



## Examples

**String**

* Input: ```_printf("%s\n", 'This is a string.');```

* Output: ```This is a string.```



**Character**

* Input: ```_printf("The first letter in the alphabet is %c\n", 'A');```

* Output: ```The first letter in the alphabet is A```



**Integer**

* Input: ```_printf("There are %i dozens in a gross\n", 12);```

* Output: ```There are 12 dozens in a gross```



**Decimal:**

* Input: ```_printf("%d\n", 1000);```

* Output:  ```1000```



## File Descriptions



* **_printf.c:** - contains the  fucntion ```_printf```, which uses the prototype ```int _printf(const char *format, ...);```. **_printf** will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to **stdout**, the standard output stream.

* **_putchar.c:** - contains the function ```_putchar```, which writes a character to stdout.

* **main.h:** - contains all function prototypes used for ```_printf```.

* **print_chars.c:** - contains the functions ```print_c```, ```print_s```, ```print_S```, and ```print_r``` which handle the conversion specifiers ```c```, ```s```, ```S```, and ```r```, respectively, as well as ```hex_print```, which prints a char's ascii value in uppercase hex

* **print_numbers.c:** - contains the functions ```print_i``` and ```print_d```, which handle the conversion specifiers ```i``` and ```d```, respectively

* **print_hex.c:** - contains the functions ```print_hex```, which prints an unsigned int in hexidecimal form, ```print_x```, ```print_X```, and ```print_p```, which handle the conversion specifiers ```x```, ```X```, and ```p```, respectively

* **print_unsigned_int.c:** - contains the functions ```print_u```, ```print_o```, and ```print_b```, which handle the conversion specifiers ```u```, ```o```, and ```b```, respectively

* **print_rot13.c** - contains the function ```print_R```, which handles the conversion specifier ```R```



## Authors

[Sunkanmi Otitolaye](https://github.com/leosuky)



[Tope Adebayo](https://github.com/TopeAdebayo)
