## printf

> write your own printf

## Welcome

> A rebuild of the standard printf function in C. printf returns the number of characters printed
> (excluding the null byte at the end of strings).
> We were not asked to handle flag characters, field width, precision, or length.

## ALX

> In ALX school we rarely use the c standard library, instead we are advised to build our our function and header as we learn.

## Description

> The function printf writes output to standard output. The function writes under the control of a format string that specifies how subsequent arguments (accessed via the variable-length argument facilities of stdarg) are converted for output.

## Prototype

> int _printf(const char *format, ...);

## Return Value

> Upon successful return, _printf returns the number of characters printed

<u> ## Format of the Argument String </u>

> The format string argument is a constant character string composed of zero or more directives: ordinary characters (not %) which are copied unchanged to the output stream; and conversion specifications, each of which results in fetching zero or more subsequent arguments. Conversion specification is introduced by the character % and ends with a conversion specifier. In between the % character and conversion specifier, there may be (in order) zero or more flags, an optional minimum field width, an optional precision and an optional length modifier. The arguments must correspond with the conversion specifier, and are used in the order given.
