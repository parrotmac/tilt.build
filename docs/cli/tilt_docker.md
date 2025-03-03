---
title: Tilt CLI Reference
layout: docs
hideEditButton: true
---
## tilt docker

Execute Docker commands as Tilt would execute them

```
tilt docker [flags] -- command ...
```

### Examples

```
tilt docker -- build -f path/to/Dockerfile .
```

### Options

```
  -h, --help   help for docker
```

### Options inherited from parent commands

```
  -d, --debug                          Enable debug logging
      --klog int                       Enable Kubernetes API logging. Uses klog v-levels (0-4 are debug logs, 5-9 are tracing logs)
      --log-flush-frequency duration   Maximum number of seconds between log flushes (default 5s)
  -v, --verbose                        Enable verbose logging
```

### SEE ALSO

* [tilt](tilt.html)	 - Multi-service development with no stress

###### Auto generated by spf13/cobra on 30-Jul-2021
