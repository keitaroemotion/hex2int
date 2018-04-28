# hex2int

Converts from hexadecimal to decimal, and vice versa

# installation

```
$ ./installer
```

# usage

from hex to int

```
$ hex2int 0xasd787t8sa
```

```
$ hex2int [file name]
```

if you want to comma(,) separated result, add `-c` option.

```
$ hex2int 0xafd787b8fa -c

> 0xafd787b8fa => 755,235,272,954
```

from int to hex

```
$ hex2int 123651
```

if you want to make it upcase, add `-u` option.

```
$ hex2int 123651 -u
> 123651 => 0x1E303
```


# Todos

XXX error case handling (ex: abcd)
