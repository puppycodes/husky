# CHANGELOG

## 0.12.0

* Adds Git submodule support
* Adds Cygwin support
* Improves edge cases support (`.git` not found and `git` not in `PATH`)
* If `npm` is already present in path, doesn't load `nvm` default or `.nvmrc` version, which makes things faster in terminal. In GUI apps, the behavior is unchanged.
