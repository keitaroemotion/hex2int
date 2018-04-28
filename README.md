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
$ hex2int 0xasd787t8sa -c

> 0xafd787t8fa => 755,235,227,898
```

from int to hex

```
$ hex2int 123651
```

if you want to make it upcase, add `-u` option.

```
$ hex2int 123651 -u
```


# Todos

XXX error case handling (ex: abcd)
