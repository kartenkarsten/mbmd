## mbmd version

Show MBMD version

### Synopsis

Show MBMD version

```
mbmd version [flags]
```

### Options inherited from parent commands

```
  -a, --adapter string   Default MODBUS adapter. This option can be used if all devices are attached to a single adapter.
                         Can be either an RTU device (/dev/ttyUSB0) or TCP socket (localhost:502).
                         The default adapter can be overridden per device (default "/dev/ttyUSB0")
  -b, --baudrate int     Serial interface baud rate (default 9600)
      --comset string    Communication parameters for default adapter, either 8N1 or 8E1.
                         Only applicable if the default adapter is an RTU device (default "8N1")
  -c, --config string    Config file (default is $HOME/mbmd.yaml)
  -h, --help             Help for mbmd
      --raw              Log raw device data
  -v, --verbose          Verbose mode
```

### SEE ALSO

* [mbmd](mbmd.md)	 - ModBus Measurement Daemon

###### Auto generated by spf13/cobra on 13-Aug-2019
