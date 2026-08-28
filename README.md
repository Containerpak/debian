# Debian (cpak)

## Installation

```bash
cpak install github.com/containerpak/debian
```

Create a persistent environment and open Bash:

```bash
cpak environment create --name Debian --origin github.com/containerpak/debian
cpak environment shell --environment Debian --command /bin/bash
```

The environment keeps its root filesystem and private home between sessions. It has network access for `apt`; host files, desktop services and devices are not exposed by default.
