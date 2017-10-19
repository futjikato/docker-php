This git project contains several preconfigured PHP environments as base for different kind of projects.

Each flavour should get an own branch, prefixed by the version and name of the inherited image and suffixed with the special purpose. `<base>-<purpose>`

e.G. `7.0-fpm-alpine-smyfony` where `7.0-fpm-alpine` is the name of the base image and `symfony` means that this image should be used for symfony projects.

The branch name must then be added to docker hub in order to use this image via `FROM interlutions/php:<version>-<base>-<purpose>`