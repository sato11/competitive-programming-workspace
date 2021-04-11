# competitive-programming-workspace
A personal workspace. Works on macOS Catalina (10.15.7).

## how-to-use
Make `.cpp` file, code, compile with a shortcut `command + shift + B` and run the executable.

Note that any artifact is not supposed to be committed. This is only a workspace. Never try to keep the record of submissions here.

## provision
### install gcc
Fetch gcc via homebrew:

```
brew install gcc
```

This enables the executable `x86_64-apple-darwin19-g++-10`, on which we depend.

### install ac-library
Fetch [atcoder/ac-library](https://github.com/atcoder/ac-library) and place it in the include path:

```
git clone git@github.com:atcoder/ac-library.git
cd ac-library
cp -r atcoder /usr/local/include/atcoder
```
