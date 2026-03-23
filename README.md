# madOS Updates

This repository hosts madOS update packages and releases.

## Structure

```
mados-updates/
├── releases/
│   └── stable/
│       ├── releases.json      # Release metadata
│       └── mados-*.tar.gz     # Update packages
└── README.md
```

## Using Updates

madOS clients use `mados-updater` to check and install updates from this repository.

For more information about the update system, see the [mados-updater](https://github.com/madkoding/mados-updater) repository.
