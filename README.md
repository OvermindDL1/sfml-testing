Testing example project for minimal setting up of SFML 2.5 in CMake

### Steps

Adjust steps as appropriate for what is wanted.

First git clone it:

```zsh
git clone --recursive https://github.com/OvermindDL1/sfml-testing.git
cd sfml-testing
```

Then make a build:

```zsh
cmake -H. -B_builds -DCMAKE_BUILD_TYPE=Release
```

Then build it:

```zsh
cmake --build _builds
```

Then run it (just a pure black OpenGL window that exits when the window is closed):

```zsh
./_builds/sfml-testing
```
