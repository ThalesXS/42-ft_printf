<p align="center">
  <img src="srcs/ft_printf.png" />
</p>

<h1 align="center">ft_printf</h1>

[Subject](srcs/en.subject.pdf)

&nbsp; In this project we must recreate the `printf()` function while following a set of rules. To do so, we must recreate the following conversions:

* Conversions: `%`, `c`, `s`, `p`, `i`, `d`, `u`, `x`, `X`.

&nbsp; And for it's bonuses, we must implement the following flags and options:

* Flags: `#`, `+` and `(space)`.
* Options: `-`, `0`, `.`, `*` and `width`.

&nbsp; The main point of this project is for us to learn how the `printf()` function works and what Variadic Arguments are.

## Usage
``make`` to compile mandatory functions.

``make bonus`` to compile with bonus functions.

> [!ATTENTION]
> Since it's not easy to implement the bonuses after the completion of the mandatory part, both `make` and `make bonus` will compile the same files and result in the project with its bonuses.

## Restrictions
&nbsp; We are only allowed to use the following functions:

* `write()`.
* `malloc()`.
* `free()`.
* Our own `libft` library (only functions that respect the above restrictions are allowed).
* All functions from the `vararg.h` library.