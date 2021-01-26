# lsdu

List disk usage of directory with pretty colors

Example of result:

<img alt="lsdu example screenshot" src="https://raw.githubusercontent.com/Termplexed/lsdu/lsdu-sample-image/lsdu.png" />

### Options

```tex
$ lsdu -h
Usage: lsdu [OPTION|DIRECTOR(Y|IES)]
  Options:
    --     Everything after this is treated as directories.
    -c     Use color on sizes. Default on.
    -C     Use colors on names. Default on.
    -d     Print directories. Default on
    -f     Print files in root directory. Default on.
    -r     Same as -f.
    -rt    Print root total. Default on.
    -si    Use units of 10^x instead of 2^x. Default 2^x
    -z  S  Use specific size. b B k K m M g G t T where lower
           case is 10^x and upper 2^x. h is human and best fit
           is used. Default "h".
    -p  N  Precision to use. Default 1.
    -h     This help.

  Every option can be prefixed with `n' no negate. E.g. -nc.
```
