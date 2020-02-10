rsum
====

This command generates a recursive hash of a directory. It outputs one line per
file. Each line is formatted as the hash, followed by two spaces, followed by
the relative file path. This is identical to the format of md5sum and the
various shaXsum tools.

Quickstart
----------

Example invocation:

```
rsum .
```

Example ouput:

```
ade6cfd195eb8c4abacb28fdcd148ee368aeb606cc7788b0841149ee75a88f4f  ./dir1/file2.txt
e74cb87780ff43c368cfcc6801447361dc1f241c4fd7f51c4ec002ebc053eced  ./dir1/file3.txt
0c3ecec7df2ecb51be447f876eca3408d25a0d81b54adc022f09927d63cbf199  ./file1.txt
```

Advanced Usage
--------------

The command accepts multiple paths, which will be included in the output in the
order in which they are passed.

The --verbose or -v option triggers verbose mode.
