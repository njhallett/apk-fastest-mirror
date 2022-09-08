# apk fastest mirror

Taken from https://wiki.alpinelinux.org/wiki/Finding_the_fastest_mirror for easy download on console.

## Usage

```sh
apk-fastest-mirror.sh [-t timelimit]
```

Processing will exit the list of mirrors when a mirror is found to be less than or equal to the `timelimit`. If this value is zero (the default) then the whole list is processed.
