# ft_printf
ft_printf is a project in C language that mimics the real `printf()` function.

## You need to implement the `libc printf()` function.
- The `ft_printf()` prototype should be: `int  ft_printf(const char *, ...);`

## Here are some requirements to follow:
- Unlike the original `printf()` function, you don't have to manage a buffer.
- You must handle the following conversions: `cspdiuxX%`
- Your output will be compared to the original printf() function.
- You must use the `ar` command to create your library. The use of the `libtool` command is prohibited.
- Your `libftprintf.a` must be created at the root of your repository.

## You must implement the following conversions:
- `%c` Displays a single character.
- `%s` Displays a character string (as defined by the C convention).
- `%p` The `void *` pointer argument must be displayed in hexadecimal.
- `%d` Displays a decimal number (base 10).
- `%i` Displays a base 10 integer.
- `%u` Displays an unsigned decimal number (base 10).
- `%x` Displays a number in hexadecimal (base 16) with lowercase letters.
- `%X` Displays a number in hexadecimal (base 16) with uppercase letters.
- `%%` Displays a percent sign.

## List of bonuses:
- Support any combination of the following flags: '`-0.`' and minimum field width with all conversions.
- Support all of the following flags: '`#+`' (Yes, space is a valid flag)
