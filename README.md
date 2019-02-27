# Nim version manager

Nim version manager. Maybe multi-platform


## Commands

- `./bin/install [version]`: install specific version.
- `./bin/home [version]`: return home directory path of specific version.
- `./bin/bin [version]`: return bin directory paths of specific version.
- `./bin/installed`: list installed versions.
- `./bin/versions`: list versions that can be installed.
- `eval $(./bin/env [version])`: set up the environment of specific version.


## Requirements

- `gcc`: required for `./bin/install`
- `wget` or `curl`: required for `./bin/install`
- `git`: required for `./bin/versions`
- `bash`: required for Windows
