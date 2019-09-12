# ft_printf
42 Project: A hand-made version of the famous C function, printf.

To compile, run 'make'. This will compile a beautiful library called 'libftprintf.a' that you'll be able to include in all your projects. This library also contains a house-made C standard library, used for ft_printf().

Handled features:

conversions: 
  - c, s, p,
  - d, i, o, u, x, X with the following flags: hh, h, l and ll.
  - f with the following flags: l and L.

options and flags:
  - %%
  - #0-+ and space
  - minimum field-width
  - precision
