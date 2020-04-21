## TODO:
1. Allow one core to handle one rxq and not restrict to handle full port.
2. Remove stuff from l2fwd which is not needed.

## Sample command:

```
sudo ./build/app/l2fwd -c 0x5555 -w 0000:05:08.0 -w 0000:05:08.1 -w 0000:05:08.2 -w 0000:05:08.3 --socket-mem "256,256" --log-level=8 -- -p 0xF
```
