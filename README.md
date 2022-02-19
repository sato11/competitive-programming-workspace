# cpp-sandbox
A personal workspace. Works on macOS Monterey (12.1).

## how-to-use
Make `.cpp` file, code, compile with a shortcut `command + shift + B` and run the executable.

Note that any artifact is not supposed to be committed. This is only a workspace. Never try to keep the record of submissions here.

## provision
### install gcc
Fetch gcc@9 via homebrew:

```
brew install gcc@9
```

This enables the executable `/usr/local/bin/g++-9`, on which we depend.

#### Waiver
Aliasing `g++` to `g++-9` in dotfiles and simply calling `g++` in `tasks.json` do not help. Perhaps `tasks.json` does not load the alias on the fly. Will need to be worked on. However we have fixed the version to 9 at least and are definitely happier than before :)

### install ac-library
Fetch [atcoder/ac-library](https://github.com/atcoder/ac-library) and place it in the include path:

```
git clone git@github.com:atcoder/ac-library.git
cd ac-library
cp -r atcoder /usr/local/include/atcoder
```
