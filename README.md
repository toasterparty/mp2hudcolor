# mp2hudcolor
Sets a user-defined HUD color for Metroid Prime 2: Echoes. Values are stored as R/G/B where values are 0.0 to 1.0.

Build instructions all are written for Linux, but should adapt fine for Win.

# Standalone

## Usage
```sh
# mp2hudcolor <input> <output> <red> <green> <blue>
mp2hudcolor Standard.ntwk Standard-out.nkwk 1.0 0.5 0.25
```
## Build
```sh
tools/build-standalone.sh
```

# Cython Package

## Requirements
```sh
# Tested with python3.10
apt install python3.X-venv
apt install python3.X-dev
```

## Build (Cython Package)
```
tools/venv.sh
tools/build-cython.sh
```
