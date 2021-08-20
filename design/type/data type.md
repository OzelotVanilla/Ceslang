Introduction
=================

*To Do: not complete*.

All type in Cesno is object. You can extend it, or 

Supported Types
=================

1. Commonly used types

| Type    | Type Name                        | Description                                              | Literal               |
| ------- | -------------------------------- | -------------------------------------------------------- | --------------------- |
| `int`   | integer type                     | save numbers from `-2^(31)` to `2^(31)-1`, edge included | `64`, `1024`          |
| `float` | floating point type / float type | follow IEEE double precision floating point type         | `0.5`, `1.0`          |
| `bool`  | bool/boolean type                | save `true` or `false`                                   | `true`, `false`       |
| `char`  | char type                        | save one UTF-8 encoded character                         | `'a'`, `'b'`          |
| `str`   | string type                      | save sequence of char                                    | `"string"`, `"Cesno"` |

2. Other useful types

| Type   | Type Name        | Description                                                    | Literal                  |
| ------ | ---------------- | -------------------------------------------------------------- | ------------------------ |
| `dgtn` | Digit *n* (type) | *n* should be a number include 8, 16, 32... It should be `2^n` | `3d8`, `12345678900d128` |
| `num`  | Numeric Type     | Save numbers with unlimited length (small than memory)         | `1.3n`, `12341234n`      |
| `cplx` | Complex type     | Complex number (math)                                          | `2i`, `1+2i`             |
| `alge` | Algebra type     | For precise calculate like sci calculate                       | `0a`, `100a`             |
