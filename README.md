# Usage

1. `yarn install`
2. `yarn build`

# Error

> Setting version to `14.16.0` (LTS) does not work.

`node_repositories(node_version = "14.16.0")` causes:

```
ERROR: no such package '@nodejs_linux_amd64//': Unknown NodeJS version-host 14.16.0-linux_amd64
```

But

`node_repositories(node_version = "14.15.5")` works fine
